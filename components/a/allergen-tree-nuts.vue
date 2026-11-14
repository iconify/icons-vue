<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itp4elb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:allergen-tree-nuts" /></template>
<style>
.itp4elb2t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m8.333 1.554Q17 6.739 17 10.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H16V12q0 4.352-3.705 5.939Q12.154 18 12 18t-.295-.061Q8 16.352 8 12v-.75h-.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7 10.5q0-4.026 4.488-4.238l.316-.791q.027-.068.067-.13t.092-.115t.113-.094t.129-.071t.14-.045t.146-.016t.146.013t.142.041q.138.055.245.159t.165.242t.061.286q.002.149-.054.288zM9.5 12v-.75h5V12q0 3.18-2.5 4.424Q9.5 15.18 9.5 12");
}

</style>
