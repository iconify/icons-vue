<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixk0nfjur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:family-friendly" /></template>
<style>
.ixk0nfjur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2 15V19q0-.205.017-.408q.017-.204.05-.406q.034-.202.083-.4q.05-.199.116-.392q.066-.194.147-.382q.082-.187.178-.368q.097-.18.207-.352q.111-.172.236-.334t.262-.314t.287-.291q.149-.14.309-.267q.16-.128.331-.241q.17-.114.348-.213q.179-.1.366-.184q.186-.084.379-.153q.192-.069.39-.122M3 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 11v-2a2.5 2.5 0 0 1 5 0v2m10.75 0l-3-3a2 2 0 0 1 3-2.25a2 2 0 0 1 3 2.25Z");
}

</style>
