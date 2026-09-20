<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uurlk9r4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uurlk9r4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:file-line" /></template>
