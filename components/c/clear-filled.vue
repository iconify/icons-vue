<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3_4-2gzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_4-2gzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:clear-filled" /></template>
