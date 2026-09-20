<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0i_rxhzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n0i_rxhzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:coverage-outline" /></template>
