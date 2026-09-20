<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytf2gtbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ytf2gtbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-down" /></template>
