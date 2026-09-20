<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvb1kt3oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvb1kt3oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:comment-line" /></template>
