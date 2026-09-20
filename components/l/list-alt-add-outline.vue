<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwyk9ybzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-alt-add-outline" /></template>
<style>
.gwyk9ybzv {
  fill: currentColor;
  d: path("M17.423 22.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zM5 19V5zm.616 1q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v8.325q-.238-.102-.479-.181q-.24-.08-.521-.14V5.615q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192h6.808q0 .256.026.508t.088.492zm3.049-3.683q.22-.221.22-.549t-.222-.548t-.549-.22t-.548.222t-.22.549t.222.547t.549.22t.548-.221m0-3.77q.22-.22.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.55t.222.547t.549.22t.548-.221m0-3.77q.22-.221.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.549t.222.548t.549.22t.548-.221m2.527 3.721h5.385v-1h-5.385zm0-3.77h5.385v-1h-5.385zm0 7.54h2.004q.143-.287.318-.528q.175-.24.382-.473h-2.704z");
}

</style>
