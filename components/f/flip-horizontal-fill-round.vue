<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkdfjcb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkdfjcb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-fill-round" /></template>
