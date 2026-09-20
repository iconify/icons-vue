<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-wa5cb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r-wa5cb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-arrow-increase-remix" /></template>
