<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu1ar6dsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tu1ar6dsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:fandom" /></template>
