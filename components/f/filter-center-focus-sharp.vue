<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6jmlnbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-center-focus-sharp" /></template>
<style>
.z6jmlnbqx {
  fill: currentColor;
  d: path("M4 20v-5h1v4h4v1zm11 0v-1h4v-4h1v5zM4 9V4h5v1H5v4zm15 0V5h-4V4h5v5zm-8.423 4.423Q10 12.846 10 12t.577-1.423T12 10t1.423.577T14 12t-.577 1.423T12 14t-1.423-.577");
}

</style>
