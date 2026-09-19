<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v2f6job7f"/><g class="y9tr6bcfx"><path class="x_rmqqbof"/><path class="g9jj7iy0q"/></g><path class="ssl9vobmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-transit" /></template>
<style>
.g9jj7iy0q {
  d: path("M38.488 39.93v2.012c0 .863-.697 1.558-1.562 1.558H11.075a1.557 1.557 0 0 1-1.563-1.558V39.93");
}

.ssl9vobmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.095 35.75h6.112v2.417h-6.112zm21.698 0h6.112v2.417h-6.112z");
}

.v2f6job7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.033 12.611V32.58c0 .768-.62 1.387-1.39 1.387H11.357c-.77 0-1.39-.619-1.39-1.387V12.61S11.818 7.608 24 7.608s14.033 5.003 14.033 5.003M9.966 26.505h28.067");
}

.x_rmqqbof {
  d: path("M40.3 11.008V38.32c0 .892-.72 1.61-1.614 1.61H9.314a1.61 1.61 0 0 1-1.615-1.61V11.008S9.85 5.2 24 5.2s16.3 5.808 16.3 5.808M18.46 4.5h11.08");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
