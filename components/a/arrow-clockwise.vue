<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzy7cxw4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uzy7cxw4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-clockwise" /></template>
