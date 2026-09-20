<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="eykjhtb8h"/><path class="wxoy2_g_f"/><path class="w7_nbbcbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eye-hide-20-regular" /></template>
<style>
.eykjhtb8h {
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708l3.5 3.498a8.097 8.097 0 0 0-3.366 5.046a.5.5 0 1 0 .98.204a7.09 7.09 0 0 1 3.107-4.528L7.953 8.66a3.5 3.5 0 1 0 4.886 4.886l4.307 4.308a.5.5 0 0 0 .708-.708l-15-15zm9.265 10.68A2.5 2.5 0 1 1 8.673 9.38l3.446 3.447z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.w7_nbbcbd {
  d: path("M10 6c-.57 0-1.129.074-1.666.213l-.803-.803A7.648 7.648 0 0 1 10 5c3.693 0 6.942 2.673 7.72 6.398a.5.5 0 0 1-.98.204C16.058 8.327 13.207 6 10 6z");
  fill: currentColor;
}

.wxoy2_g_f {
  d: path("M10.123 8.002l3.375 3.374a3.5 3.5 0 0 0-3.374-3.374z");
  fill: currentColor;
}

</style>
