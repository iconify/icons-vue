<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzyrb-kwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comments-disabled" /></template>
<style>
.yzyrb-kwf {
  fill: currentColor;
  d: path("M21.11 22.53L15.579 17H4.616q-.691 0-1.153-.462T3 15.385V4.805q0-.095.01-.172t.029-.174L1.887 3.308l.713-.714l19.223 19.223zM21 18.184L16.317 13.5H17.5v-1h-2.183l-2-2H17.5v-1h-5.183l-2-2H17.5v-1H9.317L5.817 3h13.568q.69 0 1.153.463T21 4.615zM6.5 13.5h5.579l-1-1H6.5zm0-3h2.579l-1-1H6.5z");
}

</style>
