<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d_vg57b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-lightning-16-filled" /></template>
<style>
.d_vg57b3k {
  fill: currentColor;
  d: path("M9 1v3.5A1.5 1.5 0 0 0 10.5 6H14v7.5a1.5 1.5 0 0 1-1.5 1.5h-7c-.207 0-.405-.042-.584-.118l4.127-3.853c1.09-1.017.482-2.793-.91-3.008l.348-1.047A1.5 1.5 0 0 0 7.058 5H4V2.5A1.5 1.5 0 0 1 5.5 1zm1 .25V4.5a.5.5 0 0 0 .5.5h3.25zM1.503 12h1.75l-.59 2.36c-.12.482.463.826.827.486l4.872-4.548A.75.75 0 0 0 7.85 9H6.752l.781-2.342A.5.5 0 0 0 7.06 6H3.586a.5.5 0 0 0-.462.308l-2.083 5a.5.5 0 0 0 .461.692");
}

</style>
