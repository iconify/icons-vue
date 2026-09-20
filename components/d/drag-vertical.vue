<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydn3x3baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydn3x3baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drag-vertical" /></template>
