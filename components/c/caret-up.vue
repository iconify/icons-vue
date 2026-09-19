<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-6mogbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":384};
const content = `<path class="z-6mogbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-up" /></template>
