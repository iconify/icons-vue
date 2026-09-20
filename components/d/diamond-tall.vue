<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oslo0obqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oslo0obqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:diamond-tall" /></template>
