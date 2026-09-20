<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsc-9cd3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsc-9cd3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loop-left-ai-fill" /></template>
