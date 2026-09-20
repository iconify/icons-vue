<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vavkcib3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vavkcib3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-ai-fill" /></template>
