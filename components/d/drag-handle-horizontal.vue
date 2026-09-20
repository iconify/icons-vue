<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6fdqyvmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h6fdqyvmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:drag-handle-horizontal" /></template>
