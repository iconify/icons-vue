<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_i1dsbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i_i1dsbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:duffle-fill" /></template>
