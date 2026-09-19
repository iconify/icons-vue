<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s32tp0bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s32tp0bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:google-gemini" /></template>
