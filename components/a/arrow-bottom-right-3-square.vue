<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjwetpb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjwetpb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-3-square" /></template>
