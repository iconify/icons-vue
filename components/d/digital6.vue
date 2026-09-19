<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j21hu4qcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j21hu4qcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital6" /></template>
