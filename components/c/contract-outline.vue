<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os4iqvb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="os4iqvb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:contract-outline" /></template>
