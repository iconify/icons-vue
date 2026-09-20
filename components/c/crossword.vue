<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pon1rub3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crossword" /></template>
<style>
.pon1rub3t {
  fill: currentColor;
  d: path("M9.25 21v-5.48h5.48V21zM3 14.75V9.27h5.48v5.48zm6.25 0V9.27h5.48v5.48zm6.25 0V9.27H21v5.48zm0-6.25V3H21v5.5z");
}

</style>
