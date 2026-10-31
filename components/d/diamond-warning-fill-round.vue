<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekrb82o1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekrb82o1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-warning-fill-round" /></template>
