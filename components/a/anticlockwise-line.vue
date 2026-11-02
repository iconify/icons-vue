<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r05__4bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r05__4bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anticlockwise-line" /></template>
