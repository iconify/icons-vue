<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qgxd78b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:beaker-add-20-filled" /></template>
<style>
.qgxd78b-g {
  fill: currentColor;
  d: path("M5.5 3.5A.5.5 0 0 1 6 3h8a.5.5 0 0 1 0 1h-.996v4.684q0 .258.038.511A5.5 5.5 0 0 0 9.6 12H5.685l.89-1.653a3.5 3.5 0 0 0 .42-1.66V4H6a.5.5 0 0 1-.5-.5m3.5 11a5.5 5.5 0 0 1 .207-1.5h-4.06l-.965 1.79a1.5 1.5 0 0 0 1.32 2.212H9.6A5.5 5.5 0 0 1 9 14.5m10 0a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15z");
}

</style>
