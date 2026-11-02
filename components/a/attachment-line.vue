<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_x2sib4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_x2sib4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-line" /></template>
