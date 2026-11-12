<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sws7-4h2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewall-fill" /></template>
<style>
.sws7-4h2o {
  fill: currentColor;
  d: path("M10.5 7.5c0-.317-.068-.455-.219-.725a8 8 0 0 1-.175-.328c-.355-.71-.455-1.482-.217-2.245c.253-.808.837-1.463 1.486-1.983a1.002 1.002 0 0 1 1.606.585c.199.997.818 1.795 1.619 2.396a1 1 0 0 1 .107.093C15.71 6.296 16 7.626 16 9a4 4 0 0 1-.315 1.557A3.998 3.998 0 0 1 8 9c0-.789.22-1.632.791-2.205A.997.997 0 0 1 10.5 7.5M2 17a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm2 0h4v-1H5a.997.997 0 0 0-1 1m16 0a1 1 0 0 0-1-1h-9v1ZM5 20h9v-1H4a1 1 0 0 0 1 1m11 0h3a1 1 0 0 0 1-1h-4Z");
}

</style>
