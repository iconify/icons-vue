<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d80982hzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fireplace-fill" /></template>
<style>
.d80982hzn {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 0 2h-1v16h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1V4H3a1 1 0 0 1 0-2Zm-3 2H6v16h12Zm-9.834 7.42l.002-.002a.999.999 0 0 1 1.707.707c0 .101.06.193.154.232a.25.25 0 0 0 .346-.232c0-.187-.015-.38-.075-.558c-.056-.165-.146-.32-.23-.471a9 9 0 0 1-.214-.399C8.867 8.718 9.775 7 11.375 5.719a1.002 1.002 0 0 1 1.606.585c.263 1.315 1.062 2.353 2.119 3.146a1 1 0 0 1 .107.093c1.209 1.21 1.543 2.802 1.543 4.457a4.7 4.7 0 0 1-.374 1.849A4.752 4.752 0 0 1 7.25 14c0-.919.249-1.911.916-2.58");
}

</style>
