<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y__k4ac1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y__k4ac1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cursor-click-solid" /></template>
