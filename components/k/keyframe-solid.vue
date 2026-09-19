<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq8dorxuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq8dorxuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-solid" /></template>
