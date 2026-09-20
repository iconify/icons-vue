<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfy_3jb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:adf-scanner-outline-sharp" /></template>
<style>
.sfy_3jb9s {
  fill: currentColor;
  d: path("M3.577 19.385v-6.77H7V4.847h10v7.77h3.423v6.769zM8 12.615h8V5.847H8zm-3.423 5.77h14.846v-4.77H4.577zm13.039-2.154q.425 0 .712-.288t.288-.712t-.288-.713t-.712-.287t-.713.287t-.287.713t.287.712t.713.288M4.577 13.615h14.846z");
}

</style>
