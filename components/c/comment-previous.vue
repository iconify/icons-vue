<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0ignm61z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w0ignm61z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:comment-previous" /></template>
