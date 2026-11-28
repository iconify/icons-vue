<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvbrrab-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvbrrab-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-u-turn-left-line-flip-solid" /></template>
