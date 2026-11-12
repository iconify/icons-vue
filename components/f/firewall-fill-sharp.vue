<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j41axubww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewall-fill-sharp" /></template>
<style>
.j41axubww {
  fill: currentColor;
  d: path("M10.5 7.5c0-.317-.068-.455-.219-.725a8 8 0 0 1-.175-.328c-.355-.71-.455-1.482-.217-2.245c.253-.808.837-1.463 1.486-1.983a1.002 1.002 0 0 1 1.606.585c.199.997.818 1.795 1.619 2.396a1 1 0 0 1 .107.093C15.71 6.296 16 7.626 16 9a4 4 0 0 1-.315 1.557A3.998 3.998 0 0 1 8 9c0-.789.22-1.632.791-2.205A.997.997 0 0 1 10.5 7.5M2 15a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm6 1H4v1h4Zm12 1v-1H10v1ZM4 20h10v-1H4Zm16 0v-1h-4v1Z");
}

</style>
