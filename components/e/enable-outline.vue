<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i63yuvbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:enable-outline" /></template>
<style>
.i63yuvbxm {
  fill: currentColor;
  d: path("M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12q0-3.011 1.81-5.399T9.5 3.354v1.073q-2.467.81-3.984 2.89T4 12q0 3.35 2.325 5.675T12 20t5.675-2.325T20 12q0-2.604-1.516-4.684T14.5 4.427V3.354q2.88.86 4.69 3.247T21 12q0 1.864-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71M12 15.289L7.692 10.98l.708-.708l3.1 3.094V3.02h1v10.348l3.1-3.094l.708.708z");
}

</style>
