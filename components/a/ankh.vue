<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkyzdbc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="bkyzdbc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ankh" /></template>
