<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct4c3sv7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct4c3sv7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-resize-landscape" /></template>
