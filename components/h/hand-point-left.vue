<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4aagl8dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x4aagl8dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-point-left" /></template>
