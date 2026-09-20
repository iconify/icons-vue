<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a761kcb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-one-outline-sharp" /></template>
<style>
.a761kcb_m {
  fill: currentColor;
  d: path("M12.5 16.5h1v-9h-3v1h2zM20 20H4V4h16zM5 19h14V5H5zM5 5v14z");
}

</style>
