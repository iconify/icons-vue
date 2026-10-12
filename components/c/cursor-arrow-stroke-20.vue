<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj44subkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qj44subkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cursor-arrow-stroke-20" /></template>
