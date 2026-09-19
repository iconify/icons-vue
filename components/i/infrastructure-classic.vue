<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_wkv8bja.css';
import '../../css/p/pv_j-gb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y_wkv8bja"/><path class="pv_j-gb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:infrastructure-classic" /></template>
