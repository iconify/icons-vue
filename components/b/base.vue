<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqvar9byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1280};
const content = `<path class="jqvar9byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:base" /></template>
