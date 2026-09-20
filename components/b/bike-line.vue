<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tofxyuz8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tofxyuz8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bike-line" /></template>
