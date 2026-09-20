<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue-sjgbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ue-sjgbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:calendar-16" /></template>
