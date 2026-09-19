<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi65dfb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="hi65dfb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-2-duo" /></template>
