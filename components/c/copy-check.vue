<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frjtak0tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="frjtak0tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:copy-check" /></template>
