<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfkb83bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pfkb83bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:left-align-outline" /></template>
