<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg6_6qt2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cg6_6qt2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:compsition-horizontal" /></template>
