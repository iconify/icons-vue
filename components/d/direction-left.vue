<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2g4ygt8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="c2g4ygt8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-left" /></template>
