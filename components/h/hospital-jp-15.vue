<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhx4xggnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zhx4xggnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hospital-jp-15" /></template>
