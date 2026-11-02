<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdjb4f5fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdjb4f5fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-compare-fill" /></template>
