<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5j01ib0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r5j01ib0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:dumpster" /></template>
