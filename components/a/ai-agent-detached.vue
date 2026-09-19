<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7o6ebmtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7o6ebmtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-agent-detached" /></template>
