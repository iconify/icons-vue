<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6cdozt2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g6cdozt2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloudy-sun" /></template>
