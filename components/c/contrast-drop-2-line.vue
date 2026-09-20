<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccwlleqgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccwlleqgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contrast-drop-2-line" /></template>
