<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed5-32ims.css';
import '../../css/v/ve641vb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed5-32ims"/><path class="ve641vb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-star-line" /></template>
