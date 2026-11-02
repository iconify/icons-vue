<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quy3wgqcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quy3wgqcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:light-snow-line" /></template>
