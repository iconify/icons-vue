<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxivxha2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pxivxha2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-footprint-20-bold" /></template>
