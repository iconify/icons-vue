<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuvd9qbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tuvd9qbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:apple-core" /></template>
