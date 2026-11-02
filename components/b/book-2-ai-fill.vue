<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr-zcdbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr-zcdbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-2-ai-fill" /></template>
