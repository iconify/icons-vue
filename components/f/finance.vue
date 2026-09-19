<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6oxyd10e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6oxyd10e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:finance" /></template>
