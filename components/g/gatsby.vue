<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oudmp2tzk.css';
import '../../css/y/y2ef2wbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="oudmp2tzk"/><path class="y2ef2wbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gatsby" /></template>
