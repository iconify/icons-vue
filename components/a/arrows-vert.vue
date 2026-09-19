<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xto2pgbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xto2pgbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arrows-vert" /></template>
