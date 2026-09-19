<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1v1gjlxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":480};
const content = `<path class="z1v1gjlxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-speaker" /></template>
