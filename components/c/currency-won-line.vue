<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d954ggb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d954ggb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-won-line" /></template>
