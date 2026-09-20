<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x70bjtbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:delete-forever-outline-sharp" /></template>
<style>
.x70bjtbca {
  fill: currentColor;
  d: path("m9.4 15.808l2.6-2.6l2.6 2.6l.708-.708l-2.6-2.6l2.6-2.6l-.708-.708l-2.6 2.6l-2.6-2.6l-.708.708l2.6 2.6l-2.6 2.6zM6 20V6H5V5h4v-.77h6V5h4v1h-1v14zm1-1h10V6H7zM7 6v13z");
}

</style>
