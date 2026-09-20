<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwtnfzbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwtnfzbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-2-ai-line" /></template>
