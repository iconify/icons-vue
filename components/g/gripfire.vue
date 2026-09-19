<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx9_lb6_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sx9_lb6_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:gripfire" /></template>
