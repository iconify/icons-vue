<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo6i32hen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo6i32hen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bar-chart-alt-2" /></template>
