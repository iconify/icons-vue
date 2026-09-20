<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0z73lbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":60};
const content = `<path class="h0z73lbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alpha-vantage" /></template>
