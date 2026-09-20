<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6re21bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6re21bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:comment-dots" /></template>
