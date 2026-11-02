<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke_u_acdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-fill" /></template>
<style>
.ke_u_acdz {
  fill: currentColor;
  d: path("m18.894 6.553l3 6c.07.139.106.292.106.447v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-4c0-.155.036-.308.106-.447l3-6C5.643 5.478 6.652 4.001 8 4h8c1.348.001 2.357 1.478 2.894 2.553m-1.788.894c-.216-.431-.47-.857-.813-1.2c-.093-.093-.199-.197-.324-.247H8.031c-.124.05-.231.154-.324.247c-.343.343-.597.769-.813 1.2L4.618 12h14.764ZM6 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
