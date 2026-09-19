<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jshimbb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="jshimbb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-7-5" /></template>
