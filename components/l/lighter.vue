<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybynujiyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ybynujiyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:lighter" /></template>
