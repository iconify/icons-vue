<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp1cw-bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jp1cw-bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dent" /></template>
