<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hffinzb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hffinzb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:density-s-outline" /></template>
