<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkaybslkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":488};
const content = `<path class="xkaybslkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:grid-off" /></template>
