<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov-pcmbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov-pcmbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-back-circle" /></template>
