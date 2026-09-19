<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr8snkabi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vr8snkabi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-lowpass" /></template>
