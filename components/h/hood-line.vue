<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy-869bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy-869bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hood-line" /></template>
