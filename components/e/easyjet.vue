<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbxh-3qlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbxh-3qlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:easyjet" /></template>
