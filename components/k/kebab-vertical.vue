<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jog8yfyqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":3,"height":16};
const content = `<path class="jog8yfyqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:kebab-vertical" /></template>
