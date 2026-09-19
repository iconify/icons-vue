<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1a17le6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u1a17le6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:facility-group" /></template>
