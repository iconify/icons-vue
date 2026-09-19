<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls3v0ebdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ls3v0ebdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:landscape-orientation" /></template>
