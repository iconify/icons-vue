<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5xq4ubgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y5xq4ubgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-vis-3" /></template>
