<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx68gfb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lx68gfb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-and-flower-and-mountain-snowcapped" /></template>
