<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xejalytnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-post-office-outline-sharp" /></template>
<style>
.xejalytnm {
  fill: currentColor;
  d: path("M16 19v3H2V12h4V8q0-2.5 1.75-4.25T12 2h4q2.5 0 4.25 1.75T22 8v14h-2v-3zm0-2h4V8q0-1.65-1.175-2.825T16 4h-4q-1.65 0-2.825 1.175T8 8v4h8zm-7-.15L14 14H4zm0 1.75l-5-2.85V20h10v-4.25zM4 14v6zm6-4V8h8v2z");
}

</style>
