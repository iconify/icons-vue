<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8c9z6bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m8c9z6bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:brd" /></template>
