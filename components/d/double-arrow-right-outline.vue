<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mol7c5d1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mol7c5d1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:double-arrow-right-outline" /></template>
