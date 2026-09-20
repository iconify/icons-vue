<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv2ku9rbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="iv2ku9rbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:expand" /></template>
