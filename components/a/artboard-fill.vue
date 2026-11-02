<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzjz7ybat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzjz7ybat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:artboard-fill" /></template>
