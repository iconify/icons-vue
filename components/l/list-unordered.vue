<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4yxh5fbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t4yxh5fbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:list-unordered" /></template>
