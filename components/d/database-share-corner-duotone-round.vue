<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tm3r-ebrm"/><path class="zrzn0bbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-share-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tm3r-ebrm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.708 4.186c2.465-2.913 10.119-2.913 12.584 0C15.724 4.698 16 5.324 16 6s-.276 1.302-.708 1.814c-2.465 2.913-10.119 2.913-12.584 0C2.276 7.302 2 6.676 2 6s.276-1.302.708-1.814");
}

.zrzn0bbiw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6c0 1.657 2.686 3 6 3s6-1.343 6-3s-2.686-3-6-3s-6 1.343-6 3m0 0v10c0 1.657 2.686 3 6 3m6-13v3M3 11c0 1.657 2.686 3 6 3m7 0h4v4m0-4l-6 6");
}

</style>
