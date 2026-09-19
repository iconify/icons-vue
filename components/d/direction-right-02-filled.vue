<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyihokqvh.css';
import '../../css/y/yyovchb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gyihokqvh"/><path class="yyovchb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-right-02-filled" /></template>
