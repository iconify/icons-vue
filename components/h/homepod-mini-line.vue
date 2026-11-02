<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-g5kwbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-g5kwbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:homepod-mini-line" /></template>
