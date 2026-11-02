<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrztamb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrztamb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-2-ai-fill" /></template>
