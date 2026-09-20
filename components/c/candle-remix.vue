<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1vttlbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o1vttlbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:candle-remix" /></template>
