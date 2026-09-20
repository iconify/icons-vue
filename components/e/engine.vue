<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb31qukaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tb31qukaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:engine" /></template>
