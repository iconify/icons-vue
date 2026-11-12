<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uz9iye4tk"/><path class="a9nvjpbmz"/><path class="sdvb_kngq"/><path class="njaypgbkt"/><path class="jg20qzbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-minimalistic-broken" /></template>
<style>
.a9nvjpbmz {
  d: path("M2.62271 15.1185L2.08029 17.3766C1.69894 18.9643 2.71265 20.552 4.34414 20.9225C5.71996 21.2349 7.1352 20.5814 7.75663 19.3466L7.88464 19.0923C8.45521 17.9586 9.63921 17.2399 10.9364 17.2399H13.0636C14.3608 17.2399 15.5448 17.9586 16.1154 19.0923L16.2434 19.3466C16.8648 20.5814 18.28 21.2349 19.6559 20.9225C21.2873 20.552 22.3011 18.9643 21.9197 17.3766L20.8349 12.8603C20.2216 10.3074 19.915 9.03089 19.0453 8.19371C18.8251 7.98184 18.5819 7.79404 18.3198 7.63367C17.2841 7 15.9371 7 13.2432 7H10.7568C8.06287 7 6.71588 7 5.68024 7.63367C5.41814 7.79404 5.17486 7.98184 4.95474 8.19371C4.32815 8.79682 3.99384 9.62792 3.6266 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg20qzbix {
  stroke-linejoin: round;
  d: path("M17 14H17.0001");
}

.njaypgbkt {
  stroke-linejoin: round;
  d: path("M15 11H15.0001");
}

.sdvb_kngq {
  d: path("M12 7V6C12 5.44772 12.4477 5 13 5H14C14.5523 5 15 4.55228 15 4V3");
}

.uz9iye4tk {
  d: path("M8.5 11V12.5M8.5 12.5V14M8.5 12.5L7 12.5M8.5 12.5L10 12.5");
}

</style>
