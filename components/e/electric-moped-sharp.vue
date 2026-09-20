<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p94t3ojgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-moped-sharp" /></template>
<style>
.p94t3ojgt {
  fill: currentColor;
  d: path("m13.039 22.654l-5.116-2.577h3.385v-1.73l5.115 2.576h-3.384zm-7.616-6.768q-.73-.729-.73-1.77h-2v-6h7v5h4.23l3.77-4.658v-3.15h-3v-1h4v4.465l-4.232 5.343H9.692q0 1.038-.728 1.769q-.729.73-1.77.73t-1.771-.729m2.828-.712q.441-.441.441-1.059h-3q0 .618.442 1.059q.441.442 1.058.442t1.059-.442M5.692 6.308v-1h4v1zm11.347 9.579q-.731-.729-.731-1.77t.728-1.77t1.77-.731t1.771.728t.73 1.769t-.728 1.772t-1.769.73t-1.771-.728m2.827-.713q.442-.441.442-1.059t-.442-1.058t-1.058-.442t-1.059.442t-.441 1.058t.441 1.059t1.059.442t1.058-.442");
}

</style>
