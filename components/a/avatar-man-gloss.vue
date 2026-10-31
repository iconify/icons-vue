<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo0engb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo0engb8s wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-gloss" /></template>
