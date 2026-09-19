<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="elt4krmjv"/><path class="w9xuyzi_m"/><path class="ip51gtjok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:document-with-text" /></template>
<style>
.elt4krmjv {
  fill: var(--svg-color--d0d1d2, #d0d1d2);
  d: path("M57.792 58.54c0 3.02-2.697 5.46-6.03 5.46H13.29c-3.33 0-6.03-2.441-6.03-5.46V9.31c0-3.01 2.703-5.462 6.03-5.462h38.472c3.335 0 6.03 2.448 6.03 5.462z");
}

.ip51gtjok {
  fill: var(--svg-color--35494d, #35494d);
  d: path("M14.863 13.232h34.23c2.301 0 2.301-3.228 0-3.228h-34.23c-2.298 0-2.298 3.228 0 3.228m0 6.551h34.23c2.301 0 2.301-3.224 0-3.224h-34.23c-2.298 0-2.298 3.224 0 3.224m0 6.699h34.23c2.301 0 2.301-3.224 0-3.224h-34.23c-2.298 0-2.298 3.224 0 3.224m0 6.548h34.23c2.301 0 2.301-3.227 0-3.227h-34.23c-2.298 0-2.298 3.227 0 3.227m0 23.697h15.75c2.301 0 2.301-3.229 0-3.229h-15.75c-2.298 0-2.298 3.229 0 3.229");
}

.w9xuyzi_m {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M57.792 54.688c0 3.02-2.697 5.463-6.03 5.463H13.29c-3.33 0-6.03-2.445-6.03-5.463V5.458c0-3.01 2.703-5.459 6.03-5.459h38.472c3.335 0 6.03 2.446 6.03 5.459z");
}

</style>
