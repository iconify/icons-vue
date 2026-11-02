<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri6kwog9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri6kwog9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-end-line" /></template>
