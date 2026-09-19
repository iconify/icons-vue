<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i785jwbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i785jwbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-book" /></template>
