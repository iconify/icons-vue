<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbtm9ey6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xbtm9ey6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:copy-check-thin" /></template>
