<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuwc27sjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:browse-outline-sharp" /></template>
<style>
.xuwc27sjw {
  fill: currentColor;
  d: path("M4 20v-5h7v5zm9 0v-9h7v9zm-9-7V4h7v9zm9-4V4h7v5zM5 19h5v-3H5zm9 0h5v-7h-5zm-9-7h5V5H5zm9-4h5V5h-5z");
}

</style>
