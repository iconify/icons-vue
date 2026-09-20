<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi7l3irhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-overline-outline" /></template>
<style>
.fi7l3irhn {
  fill: currentColor;
  d: path("M5.692 4.5v-1h12.616v1zm1.836 13.972q-1.836-1.837-1.836-4.473T7.53 9.528T12 7.692t4.471 1.836T18.308 14t-1.836 4.472T12 20.308t-4.472-1.836m8.15-.794q1.514-1.514 1.514-3.678t-1.514-3.678T12 8.808t-3.678 1.514T6.808 14t1.514 3.678Q9.837 19.192 12 19.192t3.678-1.514");
}

</style>
