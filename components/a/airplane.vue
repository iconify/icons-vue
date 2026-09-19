<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nghcs4vdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nghcs4vdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:airplane" /></template>
