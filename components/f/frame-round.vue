<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvdw0obcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvdw0obcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frame-round" /></template>
