<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvbkgeawu.css';
import '../../css/y/y87l3m6qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pvbkgeawu"/><path class="y87l3m6qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ansys-wordmark" /></template>
