<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlo3x6s-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlo3x6s-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagon-line" /></template>
