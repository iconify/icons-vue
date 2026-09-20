<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfi7rnlht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-alt-add-outline-sharp" /></template>
<style>
.yfi7rnlht {
  fill: currentColor;
  d: path("M17.423 19.5h-3v-1h3v-3h1v3h3v1h-3v3h-1zM5 19V5zm-1 1V4h16v9.94q-.238-.101-.479-.18q-.24-.08-.521-.14V5H5v14h7.423q0 .263.026.513t.088.487zm4.665-3.683q.22-.221.22-.549t-.222-.548t-.549-.22t-.548.222t-.22.549t.222.547t.549.22t.548-.221m0-3.77q.22-.22.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.55t.222.547t.549.22t.548-.221m0-3.77q.22-.221.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.549t.222.548t.549.22t.548-.221m2.527 3.721h5.385v-1h-5.385zm0-3.77h5.385v-1h-5.385zm0 7.54h2.004q.143-.287.318-.528q.175-.24.382-.473h-2.704z");
}

</style>
