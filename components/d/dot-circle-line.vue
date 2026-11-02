<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh4rtsbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh4rtsbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dot-circle-line" /></template>
