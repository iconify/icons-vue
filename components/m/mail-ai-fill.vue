<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klw64wbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klw64wbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-ai-fill" /></template>
