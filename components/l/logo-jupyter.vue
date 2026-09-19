<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je6amzbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="je6amzbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-jupyter" /></template>
