<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa0h4yvth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b fa0h4yvth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chair" /></template>
