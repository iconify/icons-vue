<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ag65klb_f"/><path class="cd_xkobwx"/><path class="y4i4n29ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boligsiden" /></template>
<style>
.ag65klb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24L24 5.5L5.5 24v18.5h37z");
}

.cd_xkobwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.327V24h18.5");
}

.y4i4n29ti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.327L11.192 26.135v10.673h25.616V24");
}

</style>
