<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqk1152xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="tqk1152xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:align-justify" /></template>
