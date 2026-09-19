<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw02hh1vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nw02hh1vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:fish-fins" /></template>
