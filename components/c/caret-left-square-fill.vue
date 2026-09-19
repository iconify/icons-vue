<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muwqqh8bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="muwqqh8bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-left-square-fill" /></template>
