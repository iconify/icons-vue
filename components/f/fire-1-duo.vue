<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crh93bt4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="crh93bt4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fire-1-duo" /></template>
