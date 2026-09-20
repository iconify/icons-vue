<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm9l0rbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm9l0rbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-ai-line" /></template>
