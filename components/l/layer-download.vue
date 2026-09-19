<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5q8w5tmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m5q8w5tmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-download" /></template>
