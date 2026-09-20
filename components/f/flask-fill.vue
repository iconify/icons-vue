<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa7b79bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wa7b79bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-fill" /></template>
