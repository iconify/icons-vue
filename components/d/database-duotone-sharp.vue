<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uagj96ooh"/><path class="fa-fx9sqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-duotone-sharp" /></template>
<style>
.fa-fx9sqh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7c0 1.657 2.686 3 6 3s6-1.343 6-3s-2.686-3-6-3s-6 1.343-6 3m0 0v10c0 1.657 2.686 3 6 3s6-1.343 6-3V7M6 12c0 1.657 2.686 3 6 3s6-1.343 6-3");
}

.ft5dv1b6b {
  fill: none;
}

.uagj96ooh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.708 5.186c2.465-2.913 10.119-2.913 12.584 0C18.724 5.698 19 6.324 19 7s-.276 1.302-.708 1.814c-2.465 2.913-10.119 2.913-12.584 0C5.276 8.302 5 7.676 5 7s.276-1.302.708-1.814");
}

</style>
