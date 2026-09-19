<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntydcxbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ntydcxbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hourglass-half" /></template>
