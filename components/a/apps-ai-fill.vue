<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l57g0pdpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l57g0pdpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-ai-fill" /></template>
