<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="remypqbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charger-payment" /></template>
<style>
.remypqbar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.206 15.493q-.143-.007-.285-.021t-.283-.034q-.141-.021-.281-.048t-.279-.061t-.276-.074q-.136-.041-.271-.087q-.135-.047-.267-.1q-.133-.054-.263-.113q-.129-.059-.256-.125q-.127-.065-.25-.137q-.124-.071-.244-.149q-.12-.077-.236-.16t-.228-.171t-.22-.182t-.211-.192t-.201-.202q-.099-.103-.192-.211q-.094-.108-.182-.22t-.171-.229t-.159-.236t-.149-.244q-.071-.123-.136-.25t-.125-.257t-.112-.262t-.1-.267q-.046-.135-.086-.272q-.041-.137-.074-.276q-.034-.138-.061-.279q-.027-.14-.047-.281t-.034-.283q-.013-.142-.02-.285Q4.5 9.643 4.5 9.5V6h12v3.5q0 .626-.129 1.239m-6.144 9.011q-.089.195-.205.375t-.257.342t-.302.302t-.343.256q-.18.116-.375.205t-.401.149t-.418.091t-.426.03H3m4.75-19V6m5.5-3.5V6M13 13.5h9v7h-9Zm0 2.75h9");
}

</style>
