<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iggmv2kty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iggmv2kty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-ai-line" /></template>
