<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io2yrxapr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io2yrxapr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2x2-x-line" /></template>
