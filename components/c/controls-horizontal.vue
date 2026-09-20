<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivrd68bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ivrd68bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:controls-horizontal" /></template>
