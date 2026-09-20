<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dix33kbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dix33kbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-right-down-solid" /></template>
