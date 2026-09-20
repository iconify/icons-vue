<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjprgp5hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mjprgp5hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:cupcake" /></template>
