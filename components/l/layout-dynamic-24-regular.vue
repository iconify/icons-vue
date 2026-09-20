<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pssxaswre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-dynamic-24-regular" /></template>
<style>
.pssxaswre {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM4.5 15.5v2.25c0 .966.784 1.75 1.75 1.75H8.5v-4zm5.5 0v4h7.75a1.75 1.75 0 0 0 1.75-1.75V15.5zm-3.75-11A1.75 1.75 0 0 0 4.5 6.25V14h4V4.5zM10 14h9.5V6.25a1.75 1.75 0 0 0-1.75-1.75H10z");
}

</style>
