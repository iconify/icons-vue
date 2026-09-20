<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dedpi92mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dedpi92mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:drag-handle-vertical" /></template>
