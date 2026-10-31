<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjvwrkxaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjvwrkxaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-k-duocolor-round" /></template>
