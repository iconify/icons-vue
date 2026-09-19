<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp7tpbbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kp7tpbbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:list-thumbnails" /></template>
