<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxzmb8bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="dxzmb8bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:circle" /></template>
