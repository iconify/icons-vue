<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0xxe-6gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0xxe-6gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-right-arrow-square" /></template>
