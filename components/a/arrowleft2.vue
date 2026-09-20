<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzle8-bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nzle8-bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:arrowleft2" /></template>
