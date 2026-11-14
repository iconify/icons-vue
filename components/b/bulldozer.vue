<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chjx6g5wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bulldozer" /></template>
<style>
.chjx6g5wn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 9.75h-1.874l-.888-4.884q-.012-.064-.034-.126q-.023-.061-.056-.118t-.075-.106q-.042-.05-.092-.092q-.051-.042-.107-.074q-.057-.033-.118-.055q-.062-.022-.126-.034q-.065-.011-.13-.011H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 5v4.793q-.11.039-.202.109t-.16.165t-.103.206t-.035.227v3.819q-1.079.206-1.902 1.029Q1.75 16.447 1.75 18q0 3.75 3.75 3.75h8q3.75 0 3.75-3.75q0-3.354-3-3.708V13h4.5v7q0 1.75 1.75 1.75T22.25 20v-9q0-1.75-1.75-1.75T18.75 11v.5h-4.5v-1q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-.75 2.5v2h-6.5v-3h6.5zm-2.649-2.5H6.75v-4h2.624z");
}

</style>
