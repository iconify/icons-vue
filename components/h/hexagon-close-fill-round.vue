<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzv3ysyde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzv3ysyde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-close-fill-round" /></template>
