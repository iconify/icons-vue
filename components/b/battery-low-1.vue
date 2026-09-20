<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd-q_lbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zd-q_lbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-low-1" /></template>
