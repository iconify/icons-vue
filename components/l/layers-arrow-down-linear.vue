<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="krbey6jfz"/><path class="qqsetuabg"/><path class="mi4udvb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layers-arrow-down-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krbey6jfz {
  d: path("M16.2127 9.808L19.0212 8.685C21.0071 7.891 22 7.494 22 7C22 6.506 21.0071 6.109 19.0212 5.315L16.2127 4.192C14.2268 3.397 13.2339 3 12 3C10.7661 3 9.7732 3.397 7.7873 4.192L4.9788 5.315C2.9929 6.109 2 6.506 2 7C2 7.494 2.9929 7.891 4.9788 8.685L7.7873 9.808C9.7732 10.603 10.7661 11 12 11C13.2339 11 14.2268 10.603 16.2127 9.808Z");
}

.mi4udvb7f {
  stroke-linejoin: round;
  d: path("M12 15V21M9 18L12 21L15 18");
}

.qqsetuabg {
  d: path("M5.7661 9L4.9788 9.315C2.9929 10.109 2 10.506 2 11C2 11.494 2.9929 11.891 4.9788 12.685L7.7873 13.808C9.7732 14.603 10.7661 15 12 15C13.2339 15 14.2268 14.603 16.2127 13.808L19.0212 12.685C21.0071 11.891 22 11.494 22 11C22 10.506 21.0071 10.109 19.0212 9.315L18.2339 9");
}

</style>
