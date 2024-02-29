-- create by FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 2,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy2.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
