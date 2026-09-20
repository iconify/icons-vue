<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ho5l5_bzb"/><path class="ggnt5-yye"/><path class="svy6ywblk"/><path class="tywmglbee"/><path class="blg80tbnt"/><ellipse class="w2ofw4bvk"/><ellipse class="f4dt8orie"/><path class="hswwec_jr"/><path class="ct-st-rww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-ceuta-and-melilla" /></template>
<style>
.blg80tbnt {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M9 16h3v3H9z");
}

.ct-st-rww {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M6 22h3v1H6zm9 0h3v1h-3zm-8-7h1v1H7zm9 0h1v1h-1z");
}

.f4dt8orie {
  cx: 12px;
  cy: 13.75px;
  fill: var(--svg-color--ffac33, #ffac33);
  rx: 3px;
  ry: 0.75px;
}

.ggnt5-yye {
  fill: var(--svg-color--ffc400, #ffc400);
  d: path("M0 12h36v12H0z");
}

.ho5l5_bzb {
  fill: var(--svg-color--c60a1d, #c60a1d);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.hswwec_jr {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M7 16h1v7H7zm9 0h1v7h-1z");
}

.svy6ywblk {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M9 17v3a3 3 0 1 0 6 0v-3z");
}

.tywmglbee {
  fill: var(--svg-color--f4a2b2, #f4a2b2);
  d: path("M12 16h3v3h-3z");
}

.w2ofw4bvk {
  cx: 12px;
  cy: 14.5px;
  fill: var(--svg-color--ea596e, #ea596e);
  rx: 3px;
  ry: 1.5px;
}

</style>
