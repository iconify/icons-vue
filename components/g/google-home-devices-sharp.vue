<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6xvgl24m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:google-home-devices-sharp" /></template>
<style>
.a6xvgl24m {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v4h-2V5H4v12h7v4zm7.838-6.163q.687-.687 1.662-.687t1.663.688t.687 1.662t-.687 1.663t-1.663.687t-1.662-.687t-.688-1.663t.688-1.662M22 8v13h-9V8zm-5.575 1.425Q16 9.85 16 10.5t.425 1.075T17.5 12t1.075-.425T19 10.5t-.425-1.075T17.5 9t-1.075.425m3.563 9.563Q21 17.975 21 16.5t-1.012-2.488T17.5 13t-2.488 1.013T14 16.5t1.013 2.488T17.5 20t2.488-1.012");
}

</style>
