<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmm_bo6jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-20-regular" /></template>
<style>
.wmm_bo6jg {
  fill: currentColor;
  d: path("M15.998 5.174c1.165.412 2 1.52 2 2.826v5a5 5 0 0 1-5 5h-5a3 3 0 0 1-2.826-2h1.096c.346.597.99 1 1.73 1h5a4 4 0 0 0 4-4V8c0-.74-.403-1.385-1-1.73zM12 2a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8.434c.16.04.327.066.5.066s.34-.025.5-.066V12a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H5a2 2 0 0 0-1.954 1.577a2 2 0 0 0-1.014-.02A3 3 0 0 1 5 2zM2.5 5.5c.37 0 .692.201.865.5h.832c1.294 0 2.502.646 3.219 1.723A2.87 2.87 0 0 0 9.803 9h1.49L9.646 7.354a.5.5 0 1 1 .707-.708l2.5 2.5a.5.5 0 0 1 0 .708l-2.5 2.5a.5.5 0 1 1-.707-.707L11.293 10h-1.49a3.87 3.87 0 0 1-3.219-1.723A2.87 2.87 0 0 0 4.197 7h-.832A.999.999 0 0 1 1.5 6.5a1 1 0 0 1 1-1");
}

</style>
