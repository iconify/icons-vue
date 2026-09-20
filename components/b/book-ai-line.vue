<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4mk-iblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4mk-iblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-ai-line" /></template>
