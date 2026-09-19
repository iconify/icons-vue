<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al03c2bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="al03c2bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:array-date-time" /></template>
