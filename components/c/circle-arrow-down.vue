<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m97mmmbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m97mmmbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:circle-arrow-down" /></template>
