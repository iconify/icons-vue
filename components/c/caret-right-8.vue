<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqb2d8bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nqb2d8bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-right-8" /></template>
