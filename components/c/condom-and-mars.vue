<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7o1llbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n7o1llbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:condom-and-mars" /></template>
