<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kynj_8h9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dine-lamp-outline-sharp" /></template>
<style>
.kynj_8h9q {
  fill: currentColor;
  d: path("M3.712 20v-3.25h-.706L2 7.673h1.02l.801 6.943H9.54v2.134h-.77V20h-.865v-3.25H4.596V20zm7.788 0v-7.77H5.77v-1h12.46v1H12.5V20zm3.77 0v-3.25h-.809v-2.134h5.723l.822-6.943h1.013L21 16.75h-.654V20h-.884v-3.25h-3.328V20zM7.691 8.846v-.75q0-1.38 1.118-2.238T11.404 5h.096V2h1v3h.116q1.476 0 2.594.858t1.117 2.238v.75zm1.064-1h6.488q-.063-.879-.85-1.362T12.616 6h-1.212q-.992 0-1.788.474q-.797.474-.86 1.372m3.244 0");
}

</style>
