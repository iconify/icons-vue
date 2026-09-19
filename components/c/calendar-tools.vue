<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfsv8v-qt.css';
import '../../css/t/teb2t72mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yfsv8v-qt"/><path class="teb2t72mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calendar-tools" /></template>
