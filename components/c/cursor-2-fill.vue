<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg0z1z4jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg0z1z4jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-2-fill" /></template>
