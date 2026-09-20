<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt7jy1boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt7jy1boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:esbuild" /></template>
