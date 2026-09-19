<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvmnjt6yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vvmnjt6yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:field-required" /></template>
