<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv0ponhul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv0ponhul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-fill-round" /></template>
