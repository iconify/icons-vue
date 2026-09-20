<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjl1bob8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="tjl1bob8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:instant-picture" /></template>
