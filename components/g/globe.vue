<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udy9dlbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="udy9dlbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:globe" /></template>
