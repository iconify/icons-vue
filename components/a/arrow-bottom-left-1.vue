<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnh2cebyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnh2cebyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-1" /></template>
