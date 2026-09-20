<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqe-16brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nqe-16brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-expand" /></template>
