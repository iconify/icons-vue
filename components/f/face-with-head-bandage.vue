<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mcv_hbcsu"/><path class="xo08acc0j"/><path class="lz6ggvtuj"/><path class="zznm5qx7m"/><path class="eihetbc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:face-with-head-bandage" /></template>
<style>
.eihetbc-e {
  fill: none;
  stroke: var(--svg-color--2f2f2f, #2f2f2f);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M49 85s19.7-9.1 38 6");
}

.lz6ggvtuj {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--78909c, #78909c);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M2 78s49.7-42.7 100-55c0 0-9.7-9.3-25-12c0 0-54-9.7-70 41c0 0-2.7 9-5 26");
}

.mcv_hbcsu {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 9.6C1.7 9.6.2 79.5.2 93.3s28.6 25 63.8 25s63.8-11.2 63.8-25S126.3 9.6 64 9.6");
}

.xo08acc0j {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M35.1 51.8c0-1 .2-1.9.4-2.7c1.8-.2 3.8-.5 5.9-1.1c3.2-.8 5.5-2.3 7.3-3.9c2 1.9 3.3 4.8 3.2 8.2c-.2 5.6-4.1 10-8.7 9.9c-4.7-.2-8.3-4.9-8.1-10.4m57.8 0c0-1-.2-1.9-.4-2.7c-1.8-.2-3.8-.5-5.9-1.1c-3.2-.8-5.5-2.3-7.3-3.9c-2 1.9-3.3 4.8-3.2 8.2c.2 5.6 4.1 10 8.7 9.9c4.7-.2 8.3-4.9 8.1-10.4");
}

.zznm5qx7m {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--78909c, #78909c);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M17.5 32.2s37.3-23.7 78-14c0 0 12.2 7.5 18.5 18.8c0 0-25-5.5-43-4c-28 2.3-49.8 9.9-61.8 12.9c0 0 2.4-7.5 8.3-13.7");
}

</style>
