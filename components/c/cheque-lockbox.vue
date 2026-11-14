<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v__cr8whr"/><path class="yq4avz9qb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-lockbox" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v__cr8whr {
  d: path("M3 15V9a3.5 3.5 0 0 1 7 0v6Z");
}

.yq4avz9qb {
  d: path("M6.5 5.5H17q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T20.5 9v4.042M12.158 15H10m1.5 0v6.5M5 10.5h3m7 7h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
