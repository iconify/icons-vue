<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuv6snbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yuv6snbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jsreport-dark" /></template>
