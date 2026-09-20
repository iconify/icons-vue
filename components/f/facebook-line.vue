<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfv4xyb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vfv4xyb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:facebook-line" /></template>
