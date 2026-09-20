<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwo95fbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="vwo95fbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-down-left" /></template>
