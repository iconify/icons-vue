<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr82g6bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr82g6bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-commit-vertical" /></template>
