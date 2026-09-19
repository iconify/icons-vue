<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4u34nyhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j4u34nyhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:kebab-vertical" /></template>
