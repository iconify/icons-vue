<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chwsiybmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chwsiybmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flip-vertical-line" /></template>
