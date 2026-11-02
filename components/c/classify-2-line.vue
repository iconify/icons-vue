<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs6bfrftc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs6bfrftc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-2-line" /></template>
