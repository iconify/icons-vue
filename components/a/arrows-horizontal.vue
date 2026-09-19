<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk05hr1jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gk05hr1jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrows-horizontal" /></template>
