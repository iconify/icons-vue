<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr87l9b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr87l9b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-add" /></template>
