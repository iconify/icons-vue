<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4q0bc4lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="j4q0bc4lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:itunes" /></template>
