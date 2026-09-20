<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl6_mcbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rl6_mcbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:girl" /></template>
