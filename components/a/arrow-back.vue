<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu0f6vbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="vu0f6vbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:arrow-back" /></template>
