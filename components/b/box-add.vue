<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usj20usnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="usj20usnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:box-add" /></template>
