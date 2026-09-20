<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydla-ob9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydla-ob9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:blueprint-helmet-1-bold" /></template>
