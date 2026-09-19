<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbolue0xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gbolue0xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:jet" /></template>
