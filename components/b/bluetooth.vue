<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5mvw6bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s5mvw6bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:bluetooth" /></template>
