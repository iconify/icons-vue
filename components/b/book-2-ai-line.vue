<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd91srmzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd91srmzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-2-ai-line" /></template>
