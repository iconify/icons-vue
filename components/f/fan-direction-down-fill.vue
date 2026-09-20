<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz9ly_bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz9ly_bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-down-fill" /></template>
