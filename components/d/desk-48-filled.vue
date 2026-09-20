<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ck0h4jl_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-48-filled" /></template>
<style>
.ck0h4jl_b {
  fill: currentColor;
  d: path("M24 35.75A4.25 4.25 0 0 1 19.75 40H8.25A4.25 4.25 0 0 1 4 35.75V18.5h20zM39.75 8A4.25 4.25 0 0 1 44 12.25v26.5a1.25 1.25 0 1 1-2.5 0V16H4v-3.75A4.25 4.25 0 0 1 8.25 8zm-28.5 16a1.25 1.25 0 1 0 0 2.5h5.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
