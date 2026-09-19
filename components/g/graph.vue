<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvuj97b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wvuj97b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:graph" /></template>
