<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frpc10w6d.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="frpc10w6d"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:deep-purple-flag" /></template>
