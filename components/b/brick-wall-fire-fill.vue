<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oti0a6g5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oti0a6g5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brick-wall-fire-fill" /></template>
