<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2pgb3blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2pgb3blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-line" /></template>
