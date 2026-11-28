<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j228pcfiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j228pcfiq primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-display-duotone" /></template>
