<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvpuq0rfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vvpuq0rfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:curved-connector-outline" /></template>
