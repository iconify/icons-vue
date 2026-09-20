<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft-4nj7qx.css';
import '../../css/c/cl68f3slr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ft-4nj7qx"/><path class="cl68f3slr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:light-blue-heart" /></template>
