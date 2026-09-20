<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r95xtcble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":193.2,"height":58.2};
const content = `<path class="r95xtcble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:avid-dark" /></template>
