<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh65wbcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh65wbcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-line" /></template>
