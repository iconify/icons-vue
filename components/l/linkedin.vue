<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puwg798lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="puwg798lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:linkedin" /></template>
