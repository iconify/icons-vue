<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy8_nmbyv.css';
import '../../css/c/c7mlw_bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":418,"height":150};
const content = `<path class="xy8_nmbyv"/><path class="c7mlw_bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:capital-one" /></template>
