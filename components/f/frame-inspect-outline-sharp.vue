<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifmj30b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-inspect-outline-sharp" /></template>
<style>
.ifmj30b1d {
  fill: currentColor;
  d: path("M13.004 13.004q.804-.804.804-1.946t-.804-1.946t-1.946-.804t-1.946.803t-.804 1.947t.803 1.946t1.947.804t1.946-.804m3.09 3.804l-2.76-2.78q-.5.384-1.071.582q-.573.198-1.205.198q-1.564 0-2.657-1.093t-1.093-2.657T8.4 8.4t2.657-1.093T13.714 8.4t1.094 2.657q0 .633-.201 1.205t-.584 1.072l2.785 2.765zM4 20v-5h1v4h4v1zm11 0v-1h4v-4h1v5zM4 9V4h5v1H5v4zm15 0V5h-4V4h5v5z");
}

</style>
