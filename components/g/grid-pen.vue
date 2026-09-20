<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry89rcb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ry89rcb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:grid-pen" /></template>
