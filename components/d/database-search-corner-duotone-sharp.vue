<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tm3r-ebrm"/><path class="hc50xlb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-search-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hc50xlb9o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6c0 1.657 2.686 3 6 3s6-1.343 6-3s-2.686-3-6-3s-6 1.343-6 3m0 0v10c0 1.657 2.686 3 6 3m6-13v3M3 11c0 1.657 2.686 3 6 3m9 4a2.828 2.828 0 1 1-4-4a2.828 2.828 0 0 1 4 4m0 0l3 3");
}

.tm3r-ebrm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.708 4.186c2.465-2.913 10.119-2.913 12.584 0C15.724 4.698 16 5.324 16 6s-.276 1.302-.708 1.814c-2.465 2.913-10.119 2.913-12.584 0C2.276 7.302 2 6.676 2 6s.276-1.302.708-1.814");
}

</style>
