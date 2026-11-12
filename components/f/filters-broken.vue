<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr5xmnbwg"/><path class="bzm4__bgx"/><path class="u-x6mqgqh"/><path class="q9_xxzb_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filters-broken" /></template>
<style>
.bzm4__bgx {
  d: path("M13.5798 13.7897C13.8509 14.4737 14 15.2194 14 15.9999C14 19.3136 11.3137 21.9999 7.99995 21.9999C7.32535 21.9999 6.67676 21.8886 6.07153 21.6833");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9_xxzb_z {
  d: path("M12 20.4722C13.0615 21.4223 14.4633 22 16.0001 22C19.3138 22 22.0001 19.3138 22.0001 16C22.0001 13.2331 20.1271 10.9036 17.5799 10.2102");
}

.u-x6mqgqh {
  d: path("M2.70835 18.8306C2.25635 17.9874 2 17.0236 2 15.9999C2 13.233 3.87294 10.9035 6.42018 10.2101");
}

.wr5xmnbwg {
  d: path("M6.33148 6.02834C6.11671 6.64587 6 7.30931 6 8C6 11.3137 8.68629 14 12 14C15.3137 14 18 11.3137 18 8C18 4.68629 15.3137 2 12 2C10.9283 2 9.92229 2.28096 9.05151 2.77323");
}

</style>
