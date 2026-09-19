<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu186ptsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu186ptsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-question-mark" /></template>
