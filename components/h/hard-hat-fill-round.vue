<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_p5yv07v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_p5yv07v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-fill-round" /></template>
