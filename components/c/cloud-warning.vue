<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orupi1b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="orupi1b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cloud-warning" /></template>
