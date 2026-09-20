<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elocijlbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="elocijlbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:codetalk" /></template>
