<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na7ncnoxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="na7ncnoxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:close-compact" /></template>
