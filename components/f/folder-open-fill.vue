<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evyyoz9fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-fill" /></template>
<style>
.evyyoz9fc {
  fill: currentColor;
  d: path("M20 10H10c-.461 0-.913.117-1.326.317a4.2 4.2 0 0 0-1.105.804c-.712.712-1.201 1.613-1.518 2.563a1.001 1.001 0 0 0 1.898.632c.218-.655.542-1.289 1.034-1.781c.166-.166.353-.316.566-.419c.14-.068.294-.116.451-.116h11.103c.165.765.092 1.577-.154 2.316l-1 3c-.317.95-.806 1.851-1.518 2.563C17.785 20.525 16.933 21 16 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293L12.414 5H17a3 3 0 0 1 3 3Z");
}

</style>
