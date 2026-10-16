<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxy1xwb1c.css';
import '../../css/p/p6wlddcnr.css';
import '../../css/d/dplnbtbni.css';
import '../../css/j/jrzue2bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xxy1xwb1c"/><path class="p6wlddcnr"/><path class="dplnbtbni"/><path class="jrzue2bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bench-vice-20-bold" /></template>
