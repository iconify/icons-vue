<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb4p4fbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb4p4fbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lightbulb-ai-line" /></template>
