<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvu_tubrj.css';
import '../../css/r/ry6cqhbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvu_tubrj"/><path clip-rule="evenodd" class="ry6cqhbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-remove-folder" /></template>
