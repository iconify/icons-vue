<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bbqbs8bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-16-filled" /></template>
<style>
.bbqbs8bbu {
  fill: currentColor;
  d: path("M7.571 7C8.361 7 9 7.64 9 8.429v5.142C9 14.361 8.36 15 7.571 15H2.43C1.639 15 1 14.36 1 13.571V8.43C1 7.639 1.64 7 2.429 7zM9 4.5A1.5 1.5 0 0 0 10.5 6H14v7.5a1.5 1.5 0 0 1-1.5 1.5H9.496c.315-.418.504-.936.504-1.5v-5A2.5 2.5 0 0 0 7.5 6H4V2.5A1.5 1.5 0 0 1 5.5 1H9zM6.923 8.501L6.3 11.8l-.664-3.3H4.334L3.7 11.8l-.638-3.3H2l1.035 5h1.299l.666-3l.636 3l1.287-.001L8 8.5zM13.75 5H10.5a.5.5 0 0 1-.5-.5V1.25z");
}

</style>
