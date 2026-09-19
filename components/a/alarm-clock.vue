<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u60-i8alj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u60-i8alj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:alarm-clock" /></template>
