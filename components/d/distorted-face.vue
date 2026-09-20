<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uvkdx4b7o"/><path class="q1m1l3ksg"/><path class="hlzh1qbrj"/><path class="vboqock-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:distorted-face" /></template>
<style>
.hlzh1qbrj {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M32.07 17.22c-1.54.59-3.29-.58-4-2.51c-.78-2.11-.22-4.21 1.29-4.72c1.63-.55 3.57.56 4.2 2.57s.37 3.95-1.49 4.66M2.3 12.56c.63-2.01 2.58-3.12 4.2-2.57c1.51.51 2.07 2.62 1.29 4.72c-.71 1.93-2.47 3.11-4 2.51c-1.86-.72-2.12-2.66-1.49-4.66");
}

.q1m1l3ksg {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M31.14 22.13c-3.47.9-6.79-1.96-7.96-6.47c-1.13-4.35.02-8.92 4.08-9.73c3.24-.66 6.98 1.92 8.11 6.46s-.76 8.86-4.22 9.76ZM.52 12.38c1.13-4.54 4.86-7.11 8.11-6.46c4.06.82 5.21 5.38 4.08 9.73c-1.17 4.51-4.49 7.37-7.96 6.47S-.59 16.84.53 12.37Z");
}

.uvkdx4b7o {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M35.28 17.91c0 9.58-7.76 17.33-17.33 17.33S.61 27.47.61 17.91S8.37.57 17.94.57S35.27 8.33 35.27 17.9Z");
}

.vboqock-s {
  fill: var(--svg-color--664500, #664500);
  d: path("M22.31 31.61c-1.43.22-2.81.27-4.43.26c-1.63 0-2.8-.11-4.13-.32c-.73-.11-1.27-.59-1.26-1.51c0-.75.5-1.36 1.28-1.34c1.07.03 2.65.19 4.21.19s3.25-.11 4.35-.18c.8-.05 1.27.57 1.3 1.38c.03.98-.58 1.4-1.33 1.52Z");
}

</style>
