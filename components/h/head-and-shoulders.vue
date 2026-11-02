<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on4ugfwlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="on4ugfwlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:head-and-shoulders" /></template>
