<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqzoihxjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jqzoihxjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:forward3" /></template>
