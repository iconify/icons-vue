<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucd-8ebmt.css';
import '../../css/d/d3c-6wbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ucd-8ebmt"/><path class="d3c-6wbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:info" /></template>
