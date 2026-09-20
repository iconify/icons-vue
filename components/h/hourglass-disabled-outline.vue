<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy-6prbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hourglass-disabled-outline" /></template>
<style>
.gy-6prbae {
  fill: currentColor;
  d: path("m20.475 23.3l-1.3-1.3H4v-2h2v-3q0-1.525.713-2.863T8.7 12q-.8-.5-1.362-1.2t-.913-1.55L.675 3.5L2.1 2.075l19.8 19.8zM15.05 12.15l-1.5-1.475q1.125-.475 1.788-1.475T16 7V4H8v1.125L6.875 4l-2-2H20v2h-2v3q0 1.6-.775 2.975T15.05 12.15M8 20h8v-1.175L10.475 13.3q-1.125.475-1.8 1.475T8 17zm10 0");
}

</style>
