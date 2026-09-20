<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_eb0xbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_eb0xbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:esbuild" /></template>
