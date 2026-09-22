<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ftptbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apps-plus" /></template>
<style>
.v2ftptbxx {
  fill: currentColor;
  d: path("M11.192 19H21v-5.808h-9.808zM3 10.808h8.808V5H3zM3 19h5.808v-5.808H3zm14-8.192v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
