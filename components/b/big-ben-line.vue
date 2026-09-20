<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpzq96b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpzq96b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:big-ben-line" /></template>
