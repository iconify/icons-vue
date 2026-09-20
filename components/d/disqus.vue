<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdlbsltok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdlbsltok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:disqus" /></template>
