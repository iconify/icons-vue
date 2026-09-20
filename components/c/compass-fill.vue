<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohxr4pnsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohxr4pnsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:compass-fill" /></template>
