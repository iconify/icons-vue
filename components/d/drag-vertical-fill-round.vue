<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o77se9lzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o77se9lzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drag-vertical-fill-round" /></template>
