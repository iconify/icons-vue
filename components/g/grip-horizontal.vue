<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5vde9b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="f5vde9b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grip-horizontal" /></template>
