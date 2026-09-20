<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kgk61abgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-28-filled" /></template>
<style>
.kgk61abgl {
  fill: currentColor;
  d: path("M15.09 2.049C21.207 2.6 26 7.739 26 14c0 6.627-5.373 12-12 12S2 20.627 2 14a11.97 11.97 0 0 1 3.764-8.728a1.001 1.001 0 0 1 1.373 1.456A9.97 9.97 0 0 0 4 14c0 5.523 4.477 10 10 10s10-4.477 10-10c0-5.216-3.994-9.5-9.09-9.959a1 1 0 0 1 .18-1.992M7.862 9.24c-.574-.877.41-1.906 1.295-1.43l.085.05c1.938 1.276 3.889 2.538 5.782 3.88c.485.343.913.659 1.099.845a2.5 2.5 0 0 1-3.536 3.535c-.186-.186-.502-.614-.845-1.098c-1.089-1.535-2.915-4.307-3.88-5.782");
}

</style>
