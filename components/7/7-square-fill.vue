<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5mju5bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a5mju5bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:7-square-fill" /></template>
