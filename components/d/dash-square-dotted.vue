<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqd10_6oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aqd10_6oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dash-square-dotted" /></template>
