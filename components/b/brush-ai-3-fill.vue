<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5bc61box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5bc61box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-ai-3-fill" /></template>
