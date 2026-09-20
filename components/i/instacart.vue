<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oibh5crij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oibh5crij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:instacart" /></template>
