<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn2x2m3bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn2x2m3bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clockwise-fill" /></template>
