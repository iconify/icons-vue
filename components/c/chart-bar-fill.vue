<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zybeskbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zybeskbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-fill" /></template>
