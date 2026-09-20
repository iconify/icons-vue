<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyrk-tbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uyrk-tbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:compact-box-truck-with-greek-cross" /></template>
