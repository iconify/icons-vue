<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf4rofglg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4rofglg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-resize-square" /></template>
