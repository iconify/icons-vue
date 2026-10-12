<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8-_5gdxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8-_5gdxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ellipse-filled" /></template>
