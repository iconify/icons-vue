<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j51w7z-wj.css';
import '../../css/e/edf-x6box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j51w7z-wj"/><path class="edf-x6box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-circle-down-o" /></template>
