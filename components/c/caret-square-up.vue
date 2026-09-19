<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcdhqgb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mcdhqgb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-square-up" /></template>
