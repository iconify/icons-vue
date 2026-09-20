<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jufnowady"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cinematic-blur-outline-sharp" /></template>
<style>
.jufnowady {
  fill: currentColor;
  d: path("m4 3l2 4h3L7 3h2l2 4h3l-2-4h2l2 4h3l-2-4h5v18H2V3zm0 6v10h16V9zm0 0v10zm4 9h8v-.55q0-1.1-1.1-1.775T12 15t-2.9.675T8 17.45zm5.413-4.587Q14 12.825 14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14t1.413-.587");
}

</style>
