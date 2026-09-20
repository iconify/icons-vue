<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q71v1jb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q71v1jb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lion-and-exclamation-point" /></template>
