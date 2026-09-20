<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3io92bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3io92bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:braille" /></template>
