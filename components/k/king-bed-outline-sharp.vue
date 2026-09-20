<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdxufo51p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:king-bed-outline-sharp" /></template>
<style>
.bdxufo51p {
  fill: currentColor;
  d: path("M4.77 18h-.54l-.38-2H3v-5h2V7h14v4h2v5h-.85l-.38 2h-.54l-.38-2H5.15zm7.73-7H18V8h-5.5zM6 11h5.5V8H6zm-2 4h16v-3H4zm16 0H4z");
}

</style>
