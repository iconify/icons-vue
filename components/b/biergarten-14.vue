<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ln4bbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o5ln4bbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:biergarten-14" /></template>
