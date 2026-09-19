<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2ob06b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="c2ob06b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-down-circle" /></template>
