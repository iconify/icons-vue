<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9v5viccb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="z9v5viccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:mail-remove" /></template>
