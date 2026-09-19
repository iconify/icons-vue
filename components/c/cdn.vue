<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_dkhvbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w_dkhvbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cdn" /></template>
