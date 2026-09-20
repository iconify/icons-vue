<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGjA0coc9K)" class="vk3xgab0s"/><path fill="url(#SVGhxzbKR1B)" class="wccnolbgh"/><defs><linearGradient id="SVGjA0coc9K" x1="12" x2="12" y1="3" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="byvjz_twk"/><stop offset=".17" class="fp85m5l-p"/><stop offset=".28" class="d8aa2vczz"/><stop offset=".43" class="q3_sabe0d"/><stop offset=".67" class="o0dig7ehb"/><stop offset="1" class="g-rt16b9f"/></linearGradient><linearGradient id="SVGhxzbKR1B" x1="11.755" x2="11.755" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="n4fgvdb8f"/><stop offset=".47" class="sopke29hj"/><stop offset="1" class="j01uh5r9b"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:copi" /></template>
<style>
.byvjz_twk {
  stop-color: var(--svg-color--7c4f14, #7c4f14);
}

.d8aa2vczz {
  stop-color: var(--svg-color--f0b035, #f0b035);
}

.fp85m5l-p {
  stop-color: var(--svg-color--cf8c21, #cf8c21);
}

.ft5dv1b6b {
  fill: none;
}

.g-rt16b9f {
  stop-color: var(--svg-color--3e1e05, #3e1e05);
}

.j01uh5r9b {
  stop-color: var(--svg-color--8b4102, #8b4102);
}

.n4fgvdb8f {
  stop-color: var(--svg-color--efdf58, #efdf58);
}

.o0dig7ehb {
  stop-color: var(--svg-color--bc7908, #bc7908);
}

.q3_sabe0d {
  stop-color: var(--svg-color--734a08, #734a08);
}

.sopke29hj {
  stop-color: var(--svg-color--c67d16, #c67d16);
}

.vk3xgab0s {
  d: path("M9.5 13c.25 3.75 2.72 6.115 4.21 6.715c-1.75.77-5.79.475-5.79-6.945c0-7.455 4.475-9 6.845-9.255l2.365.515L19 3.515l.5.515c-.63.2-1.56 1.37-2 1.97c-.63-1.235-2.125-1.5-2.735-1.5c-2.9 0-5.575 3.875-5.265 8.5");
}

.wccnolbgh {
  d: path("M19 3.515c-.815.235-1.605 1.2-1.87 1.8A2.67 2.67 0 0 0 14.75 4C12.63 4 8.5 7.085 8.5 12.75c0 5.63 3.355 7 6.25 7c1.75 0 2.825-1.135 2.645-1.835c-.09-.345-.05-1.03.79-1.03s.895.515.79 1.03C18.71 19.2 16.675 21 13.25 21c-3.42 0-6.12-4.115-6.91-5.915c-.63-1.44-1.49-1.97-1.84-2.055c.42-.825 1.4-.86 1.84-.775A8.855 8.855 0 0 1 14.75 3c1.05 0 1.855.345 2.12.515A2.03 2.03 0 0 1 18.185 3c.315 0 .565.25.815.515");
}

</style>
