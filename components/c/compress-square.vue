<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnovhgbzb.css';
import '../../css/f/f-uqiuafs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vnovhgbzb"/><path class="f-uqiuafs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:compress-square" /></template>
