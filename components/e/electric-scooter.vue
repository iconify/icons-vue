<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cah0bcbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-scooter" /></template>
<style>
.cah0bcbhc {
  fill: currentColor;
  d: path("M5.116 17.5q-1.039 0-1.77-.73T2.616 15t.73-1.77t1.77-.73q.801 0 1.516.505t.937 1.495h6.07q.178-1.777 1.422-3.09q1.243-1.314 2.931-1.545l-1.515-6.904q-.058-.211-.23-.336q-.174-.125-.347-.125h-3.284v-1H15.9q.502 0 .968.341q.467.342.598.901l1.745 8.027h-.327q-1.765 0-3.017 1.252t-1.252 3.017v.462H7.57q-.223.99-.937 1.495t-1.516.505m12-.692q-.731-.731-.731-1.77t.73-1.769q.731-.73 1.77-.73q1.038 0 1.769.73t.73 1.77t-.73 1.769t-1.77.73t-1.768-.73m-4.154 5.846l-5.116-2.577h3.385v-1.73l5.115 2.576h-3.384z");
}

</style>
