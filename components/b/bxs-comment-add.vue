<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ogw43lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6ogw43lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-comment-add" /></template>
