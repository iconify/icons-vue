<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grm7v7f_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="grm7v7f_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:head-side-virus" /></template>
