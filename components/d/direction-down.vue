<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze5oi5l2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ze5oi5l2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-down" /></template>
