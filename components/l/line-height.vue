<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u34p5im3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u34p5im3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:line-height" /></template>
