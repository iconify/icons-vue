<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcv03ats.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="qpcv03ats"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flip-to-front" /></template>
