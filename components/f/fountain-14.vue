<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp_7a8bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yp_7a8bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:fountain-14" /></template>
