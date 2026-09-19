<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns5x1qb3u.css';
import '../../css/c/c-o8u9blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ns5x1qb3u"/><path class="c-o8u9blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:easel" /></template>
