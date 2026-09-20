<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbow88und.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hbow88und"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:list-outline" /></template>
