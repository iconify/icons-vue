<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh4t9foso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:earth-rise" /></template>
<style>
.mh4t9foso {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.934 5.434Q6.25 7.118 6.25 9.5t1.684 4.066T12 15.25t4.066-1.684T17.75 9.5t-1.684-4.066T12 3.75T7.934 5.434M12 3.75q3 0 3 5.75t-3 5.75T9 9.5t3-5.75M1.805 19.217q.057-.138.162-.244q.104-.106.242-.164q9.791-4.123 19.582 0q.068.028.129.07q.061.041.113.094q.052.052.093.114t.069.13t.041.141q.014.072.014.146t-.015.147t-.044.14q-.028.068-.07.129q-.041.061-.094.113q-.052.052-.114.093t-.13.069t-.141.041t-.146.014q-.074 0-.147-.015q-.072-.015-.14-.044q-9.209-3.877-18.418 0q-.068.029-.14.044t-.147.015t-.146-.014q-.073-.014-.141-.041t-.13-.069t-.114-.093t-.094-.113t-.07-.129q-.058-.137-.059-.287t.055-.287");
}

</style>
