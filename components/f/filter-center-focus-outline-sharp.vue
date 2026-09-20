<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj5sywyym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-center-focus-outline-sharp" /></template>
<style>
.xj5sywyym {
  fill: currentColor;
  d: path("M3 21v-6h2v4h4v2zm12 0v-2h4v-4h2v6zM3 9V3h6v2H5v4zm16 0V5h-4V3h6v6zm-9.125 5.125Q9 13.25 9 12t.875-2.125T12 9t2.125.875T15 12t-.875 2.125T12 15t-2.125-.875m2.838-1.412Q13 12.425 13 12t-.288-.712T12 11t-.712.288T11 12t.288.713T12 13t.713-.288");
}

</style>
