<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywa31bcfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ywa31bcfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-generate-variation-spark-remix" /></template>
