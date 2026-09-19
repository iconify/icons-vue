<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi6co0b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wi6co0b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:fonticons" /></template>
