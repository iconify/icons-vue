<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh4aqo1ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":702};
const content = `<path class="nh4aqo1ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:location" /></template>
