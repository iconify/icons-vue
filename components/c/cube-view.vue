<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39ud6bwf.css';
import '../../css/r/rhygotbxm.css';
import '../../css/d/d_xxxv6_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="e39ud6bwf"/><path class="rhygotbxm"/><path class="d_xxxv6_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cube-view" /></template>
