<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd_m56bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_m56bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-2-ai-line" /></template>
