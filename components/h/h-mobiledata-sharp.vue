<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih3eoqb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:h-mobiledata-sharp" /></template>
<style>
.ih3eoqb-u {
  fill: currentColor;
  d: path("M7.5 17V7h1v4.5h7V7h1v10h-1v-4.5h-7V17z");
}

</style>
