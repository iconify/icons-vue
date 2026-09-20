<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij0sahb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:info-rounded" /></template>
<style>
.ij0sahb8y {
  fill: currentColor;
  d: path("M12.357 16.356q.143-.143.143-.356v-4.5q0-.213-.144-.356T11.999 11t-.356.144t-.143.356V16q0 .213.144.356t.357.144t.356-.144m.077-6.956q.182-.177.182-.438t-.177-.439T12 8.346t-.438.177t-.177.439t.181.438t.434.177t.434-.177m-.43 11.6q-1.867 0-3.511-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
