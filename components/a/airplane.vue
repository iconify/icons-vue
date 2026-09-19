<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g90-vg5gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g90-vg5gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:airplane" /></template>
