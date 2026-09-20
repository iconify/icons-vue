<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoj1vqbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoj1vqbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-coordinate-system-filled" /></template>
