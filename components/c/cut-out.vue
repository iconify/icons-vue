<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rirux2j4y.css';
import '../../css/a/acwmw9bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rirux2j4y"/><path class="acwmw9bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cut-out" /></template>
