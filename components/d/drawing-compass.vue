<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y49sr1xcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y49sr1xcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:drawing-compass" /></template>
