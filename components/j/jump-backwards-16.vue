<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-farr_vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m-farr_vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:jump-backwards-16" /></template>
