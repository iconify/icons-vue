<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jweqvabsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jweqvabsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-ai-fill" /></template>
