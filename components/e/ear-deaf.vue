<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhgq8jiux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xhgq8jiux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ear-deaf" /></template>
