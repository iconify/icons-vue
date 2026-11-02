<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj_7z6yeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj_7z6yeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-line" /></template>
