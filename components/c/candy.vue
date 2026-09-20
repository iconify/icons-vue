<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn7unvyzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nn7unvyzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:candy" /></template>
