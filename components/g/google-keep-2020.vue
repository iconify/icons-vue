<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":352};
const content = `<path class="l8q9qlbeb"/><path class="owbw0bs-d"/><path class="j0s2opuwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-keep-2020" /></template>
<style>
.j0s2opuwu {
  fill: var(--svg-color--fff, #fff);
  d: path("M156 236v20h-56v-20zm-28.08-115.999l.78.006c28.323.46 51.14 23.56 51.14 51.993c0 18.56-9.72 34.8-24.32 44h-55.2C85.68 206.8 76 190.56 76 172c0-28.72 23.28-52 52-52z");
}

.l8q9qlbeb {
  fill: var(--svg-color--ffba00, #ffba00);
  d: path("M232 352H24c-13.28 0-24-10.72-24-24V24C0 10.72 10.72 0 24 0h144l88 88v240c0 13.28-10.72 24-24 24");
}

.owbw0bs-d {
  fill: var(--svg-color--ff9500, #ff9500);
  d: path("m168 0l88 88h-88z");
}

</style>
