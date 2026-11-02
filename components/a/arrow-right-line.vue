<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msy05x8yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msy05x8yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-line" /></template>
