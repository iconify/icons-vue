<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlgoy-baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-payment" /></template>
<style>
.rlgoy-baa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.206 15.493q-.143-.007-.285-.021t-.283-.034q-.141-.021-.281-.048t-.279-.061t-.276-.074q-.136-.041-.271-.087q-.135-.047-.267-.1q-.133-.054-.263-.113q-.129-.059-.256-.125q-.127-.065-.25-.137q-.124-.071-.244-.149q-.12-.077-.236-.16t-.228-.171t-.22-.182t-.211-.192t-.201-.202q-.099-.103-.192-.211q-.094-.108-.182-.22t-.171-.229t-.159-.236t-.149-.244q-.071-.123-.136-.25t-.125-.257t-.112-.262t-.1-.267q-.046-.135-.086-.272q-.041-.137-.074-.276q-.034-.138-.061-.279q-.027-.14-.047-.281t-.034-.283q-.013-.142-.02-.285Q4.5 9.643 4.5 9.5V6h12v3.5q0 .626-.129 1.239m-6.064 8.819q-.08.213-.191.411q-.112.198-.252.377q-.139.18-.305.336t-.352.285t-.392.229q-.204.1-.421.168q-.217.067-.442.102T7.5 21.5H3m4.75-19V6m5.5-3.5V6m1.5 7.5h5.5A1.75 1.75 0 0 1 22 15.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 13 18.75v-3.5a1.75 1.75 0 0 1 1.75-1.75M13 16.25h9");
}

</style>
