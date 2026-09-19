<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8xj0kbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x8xj0kbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-1" /></template>
