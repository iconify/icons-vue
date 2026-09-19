<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5592tpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="py5592tpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:file-media" /></template>
