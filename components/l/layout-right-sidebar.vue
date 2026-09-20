<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgk3cb3nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hgk3cb3nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:layout-right-sidebar" /></template>
