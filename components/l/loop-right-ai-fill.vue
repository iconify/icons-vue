<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bysttybof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bysttybof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loop-right-ai-fill" /></template>
