<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="io9s1tu0y"/><path class="u7la2bcpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:cross-mark-button" /></template>
<style>
.io9s1tu0y {
  fill: var(--svg-color--37b34a, #37b34a);
  d: path("M63.985 57.087a6.896 6.896 0 0 1-6.896 6.896H6.896A6.897 6.897 0 0 1 0 57.087V6.896A6.9 6.9 0 0 1 6.896 0h50.192a6.897 6.897 0 0 1 6.896 6.896z");
}

.u7la2bcpn {
  fill: var(--svg-color--fff, #fff);
  d: path("M46.14 9.387c-4.714 4.716-9.43 9.432-14.14 14.15q-7.074-7.071-14.15-14.15c-5.454-5.455-13.912 3-8.457 8.459c4.714 4.712 9.432 9.43 14.14 14.14c-4.712 4.714-9.431 9.432-14.14 14.14c-5.453 5.455 3 13.91 8.457 8.46q7.07-7.075 14.15-14.15q7.073 7.072 14.14 14.15c5.455 5.452 13.91-3.01 8.46-8.458q-7.075-7.072-14.15-14.15l14.15-14.15c5.452-5.453-3-13.912-8.46-8.458");
}

</style>
