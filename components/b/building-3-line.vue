<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgdzz-bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgdzz-bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-3-line" /></template>
