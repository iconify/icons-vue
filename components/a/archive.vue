<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrr4svbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rrr4svbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:archive" /></template>
