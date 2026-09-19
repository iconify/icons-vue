<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl2u2mtnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fl2u2mtnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-left-to-line" /></template>
