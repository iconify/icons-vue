<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9du5cb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x9du5cb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:list-ordered" /></template>
