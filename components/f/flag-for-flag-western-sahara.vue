<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bvteyex9r"/><path class="khrcunw1e"/><path class="pvu5whbqv"/><path class="f0ya_xb7d"/><g class="tsrlmwb5p"><path class="vc4oqsbbp"/><path class="um7ue050j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-western-sahara" /></template>
<style>
.bvteyex9r {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4z");
}

.f0ya_xb7d {
  fill: var(--svg-color--c4111b, #C4111B);
  d: path("M1.129 6.223A3.984 3.984 0 0 0 0 9v18c0 1.08.433 2.057 1.129 2.777L12 18L1.129 6.223z");
}

.khrcunw1e {
  fill: var(--svg-color--007a3d, #007A3D);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0V27z");
}

.pvu5whbqv {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 13.5h36v9H0z");
}

.tsrlmwb5p {
  fill: var(--svg-color--c4111b, #C4111B);
}

.um7ue050j {
  d: path("M19.13 20.132l1.478-1.057l1.467 1.073l-.548-1.732L23 17.353l-1.817-.014l-.556-1.73l-.575 1.724l-1.817-.006l1.462 1.079l-.567 1.726z");
}

.vc4oqsbbp {
  d: path("M17.894 18.033a3.467 3.467 0 0 1 2.817-3.405a3.467 3.467 0 1 0-.001 6.81a3.466 3.466 0 0 1-2.816-3.405z");
}

</style>
