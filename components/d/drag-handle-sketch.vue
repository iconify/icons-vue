<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e--nlzj6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e--nlzj6l wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:drag-handle-sketch" /></template>
