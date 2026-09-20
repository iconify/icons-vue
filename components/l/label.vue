<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk7o0ccjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sk7o0ccjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:label" /></template>
