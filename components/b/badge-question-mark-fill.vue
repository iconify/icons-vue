<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq8hgf16d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq8hgf16d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-question-mark-fill" /></template>
