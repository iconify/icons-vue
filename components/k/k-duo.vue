<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdypro58p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bdypro58p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:k-duo" /></template>
