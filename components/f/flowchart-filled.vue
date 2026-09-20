<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8gnc9xyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8gnc9xyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flowchart-filled" /></template>
