<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0iw95o7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="y0iw95o7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-16-9" /></template>
