<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzp36sxgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzp36sxgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-4-fill" /></template>
