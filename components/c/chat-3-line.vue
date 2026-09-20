<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zczxv27do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zczxv27do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-3-line" /></template>
