<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qna8racdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qna8racdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:cheer" /></template>
