<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd_g-pzxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yd_g-pzxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:eye" /></template>
