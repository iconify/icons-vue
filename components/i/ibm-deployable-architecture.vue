<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkgx16bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xkgx16bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-deployable-architecture" /></template>
