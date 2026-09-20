<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aamu8pcnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aamu8pcnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-angle-linear" /></template>
