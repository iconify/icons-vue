<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik_4yp-fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:graphic-eq-off-sharp" /></template>
<style>
.ik_4yp-fz {
  fill: currentColor;
  d: path("M19.833 21.26L12.5 13.927V21h-1v-8.073l-2.75-2.75v6.939h-1V9.177l-5.01-5.01l.714-.713l17.092 17.092zM4 13.308v-2.616h1v2.616zm8.5-3.62l-1-1V3h1zm3.75 3.75l-1-1V6.884h1zm2.75-.13v-2.616h1v2.616z");
}

</style>
