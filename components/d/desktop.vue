<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0l4dp1jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0l4dp1jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:desktop" /></template>
