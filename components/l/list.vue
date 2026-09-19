<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okmjdzbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="okmjdzbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:list" /></template>
