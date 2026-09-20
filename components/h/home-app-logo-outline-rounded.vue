<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t41cfbcyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-app-logo-outline-rounded" /></template>
<style>
.t41cfbcyl {
  fill: currentColor;
  d: path("M6 21q-1.25 0-2.125-.875T3 18v-6q0-.6.225-1.15t.65-.975l6-6q.425-.45.988-.663T12 3t1.125.213t1 .662l6 6q.425.425.65.975T21 12v6q0 1.25-.875 2.125T18 21zm0-2h12q.425 0 .713-.288T19 18v-6q0-.2-.075-.375T18.7 11.3l-3.825-3.85L13.4 8.9l3.6 3.6V17H7v-4.5l6.45-6.45l-.75-.75q-.2-.2-.387-.25T12 5t-.312.05t-.388.25l-6 6q-.15.15-.225.325T5 12v6q0 .425.288.713T6 19m3-4h6v-1.675l-3-3l-3 3z");
}

</style>
