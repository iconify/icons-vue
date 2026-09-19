<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbivco96l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hbivco96l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:assembly-cluster" /></template>
