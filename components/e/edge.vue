<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhon-xy1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="rhon-xy1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:edge" /></template>
