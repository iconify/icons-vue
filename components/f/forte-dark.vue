<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp84_8xrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yp84_8xrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forte-dark" /></template>
