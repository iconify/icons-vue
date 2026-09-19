<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7vnnsbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="q7vnnsbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-3-outline" /></template>
