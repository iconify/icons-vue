<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toyuwjkjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toyuwjkjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-down-right-line" /></template>
