<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ww-wmyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7ww-wmyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-bar-increase-remix" /></template>
