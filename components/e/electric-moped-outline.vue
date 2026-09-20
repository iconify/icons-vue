<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5jh3m-dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-moped-outline" /></template>
<style>
.h5jh3m-dk {
  fill: currentColor;
  d: path("M5.423 15.886q-.73-.729-.73-1.77h-2v-2.5q0-1.458 1.02-2.48q1.021-1.02 2.48-1.02h3.5v5h4.23l3.77-4.658V5.923q0-.27-.174-.442t-.442-.173h-2.385v-1h2.385q.666 0 1.14.474t.475 1.141v2.85l-4.23 5.343h-4.77q0 1.038-.728 1.768q-.729.731-1.77.731t-1.771-.729m2.828-.712q.441-.441.441-1.059h-3q0 .618.442 1.059q.441.441 1.058.441t1.059-.441M5.692 6.308v-1h4v1zm11.347 9.579q-.731-.729-.731-1.77t.728-1.77t1.77-.731t1.771.728t.73 1.769t-.728 1.772t-1.769.73t-1.771-.728m2.827-.713q.442-.441.442-1.059t-.442-1.058t-1.058-.442t-1.059.442t-.441 1.058t.441 1.059t1.059.442t1.058-.442m-6.828 7.48l-5.115-2.577h3.385v-1.73l5.115 2.576h-3.384zm-9.346-9.538h5v-4H6.19q-1.033 0-1.765.734t-.732 1.766z");
}

</style>
