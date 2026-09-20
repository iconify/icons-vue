<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkt4xdbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nkt4xdbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:copy-paste-cut-scissors" /></template>
