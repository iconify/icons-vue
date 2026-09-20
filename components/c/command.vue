<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz1n0-axz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jz1n0-axz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:command" /></template>
