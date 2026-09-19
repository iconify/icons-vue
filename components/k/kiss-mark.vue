<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtzsmobxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rtzsmobxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:kiss-mark" /></template>
