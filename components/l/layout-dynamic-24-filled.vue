<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_3006bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-dynamic-24-filled" /></template>
<style>
.r_3006bnd {
  fill: currentColor;
  d: path("M8.5 21H6.25A3.25 3.25 0 0 1 3 17.75V15.5h5.5zM21 17.75A3.25 3.25 0 0 1 17.75 21H10v-5.5h11zM8.5 14H3V6.25A3.25 3.25 0 0 1 6.25 3H8.5zm9.25-11A3.25 3.25 0 0 1 21 6.25V14H10V3z");
}

</style>
