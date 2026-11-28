<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu6m29czl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu6m29czl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:align-justify-duo" /></template>
