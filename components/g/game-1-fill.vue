<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yja058bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yja058bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:game-1-fill" /></template>
