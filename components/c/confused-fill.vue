<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxkxh2bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxkxh2bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:confused-fill" /></template>
