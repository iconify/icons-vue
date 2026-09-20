<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjsupy_xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kjsupy_xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:filter-crossed-16" /></template>
