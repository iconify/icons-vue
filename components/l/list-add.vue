<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj991ib0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oj991ib0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:list-add" /></template>
