<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj_5p1hkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hj_5p1hkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:dribbble-square" /></template>
