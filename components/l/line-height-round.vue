<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz8d_fbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz8d_fbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:line-height-round" /></template>
