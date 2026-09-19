<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb902yrex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zb902yrex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-left-double-triangle" /></template>
