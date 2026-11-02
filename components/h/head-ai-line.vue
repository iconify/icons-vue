<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm6ox6bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm6ox6bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:head-ai-line" /></template>
