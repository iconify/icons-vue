<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkkjk9bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qkkjk9bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:files" /></template>
