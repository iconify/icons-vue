<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4hsm_bxh.css';
import '../../css/j/j51w7z-wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d4hsm_bxh"/><path class="j51w7z-wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-circle-down-o" /></template>
