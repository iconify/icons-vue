<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njjw8aczg.css';
import '../../css/v/vo_ontb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="njjw8aczg"/><path class="vo_ontb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-zoom" /></template>
