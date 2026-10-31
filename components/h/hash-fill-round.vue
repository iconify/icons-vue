<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh7iqib0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh7iqib0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hash-fill-round" /></template>
