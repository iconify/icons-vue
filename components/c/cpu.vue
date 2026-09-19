<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g42dr9bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g42dr9bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:cpu" /></template>
