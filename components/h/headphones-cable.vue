<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9af41bwu.css';
import '../../css/e/eo9c1jb5g.css';
import '../../css/n/n0qwfabul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9af41bwu"/><path class="eo9c1jb5g"/><path class="n0qwfabul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:headphones-cable" /></template>
