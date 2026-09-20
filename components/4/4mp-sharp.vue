<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww-kzdf9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4mp-sharp" /></template>
<style>
.ww-kzdf9x {
  fill: currentColor;
  d: path("M12.5 11.5H14V10h1V8.5h-1v-3h-1.5v3H11v-3H9.5V10h3zm-6.5 7h1.5V14h1v3H10v-3h1v4.5h1.5v-6H6zm7.5 0H15V17h3v-4.5h-4.5zm1.5-3V14h1.5v1.5zM3 21V3h18v18z");
}

</style>
