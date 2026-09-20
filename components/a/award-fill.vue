<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvcm6ab0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcm6ab0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:award-fill" /></template>
