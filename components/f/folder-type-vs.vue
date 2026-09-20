<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4k-o_zcb"/><path class="yqgs2lrsv"/><path class="or2qprb8i"/><path class="z9de22bhe"/><path class="lt4cyacrb"/><path class="ciq207b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vs" /></template>
<style>
.ciq207b3t {
  fill: var(--svg-color--d59dff, #d59dff);
  d: path("M30.579 14.265V26.3a.86.86 0 0 1-.386.72l-5.157 3.443a.86.86 0 0 0 .377-.72V10.83a.87.87 0 0 0-.394-.72l5.174 3.445a.87.87 0 0 1 .386.71");
}

.lt4cyacrb {
  fill: var(--svg-color--ae7fe2, #ae7fe2);
  d: path("m30.202 27.02l-5.166 3.444a.87.87 0 0 1-1.131-.154L11.458 15.858a.857.857 0 0 0-1.174-.129l3.444-2.578a.86.86 0 0 1 .514-.171c.223 0 .437.085.6.24l.05.06l14.17 13.586l.06.06a.86.86 0 0 0 1.071.094z");
}

.o4k-o_zcb {
  fill: var(--svg-color--c67bdb, #c67bdb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.or2qprb8i {
  fill: var(--svg-color--5e438f, #5e438f);
  d: path("m13.72 27.423l-3.436-2.579a.86.86 0 0 1-.343-.685v-7.744a.86.86 0 0 1 .343-.686l3.435-2.578a.77.77 0 0 0-.231.685v12.902a.78.78 0 0 0 .231.685");
}

.yqgs2lrsv {
  fill: var(--svg-color--a855bf, #a855bf);
  d: path("M27.362 5.524h-9.3l-2.1 4.2h-11.7v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.z9de22bhe {
  fill: var(--svg-color--7252aa, #7252aa);
  d: path("M30.193 13.554a.86.86 0 0 0-1.07.094l-.06.06l-14.17 13.586l-.06.06a.86.86 0 0 1-1.114.069l-3.435-2.579a.857.857 0 0 0 1.165-.128c4.155-4.806 8.293-9.63 12.439-14.444a.86.86 0 0 1 .66-.3a.8.8 0 0 1 .47.138z");
}

</style>
