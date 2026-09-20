<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pez1xvcxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pez1xvcxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ai-line" /></template>
