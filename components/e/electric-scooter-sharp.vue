<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0qt-l1hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-scooter-sharp" /></template>
<style>
.u0qt-l1hq {
  fill: currentColor;
  d: path("M5.108 17.5q-1.039 0-1.766-.728t-.726-1.77t.726-1.771t1.766-.731q.81 0 1.524.505t.937 1.495h6.07q.178-1.777 1.422-3.09q1.243-1.314 2.931-1.545L16.381 2.5h-3.765v-1h4.576l2.02 9.27h-.327q-1.762 0-3.016 1.253q-1.254 1.254-1.254 3.015v.462H7.57q-.223.99-.937 1.495t-1.524.505m12.008-.69q-.731-.728-.731-1.77t.728-1.77t1.77-.731t1.77.728t.732 1.77t-.729 1.77t-1.769.732t-1.771-.729m-4.154 5.844l-5.116-2.577h3.385v-1.73l5.115 2.576h-3.384z");
}

</style>
