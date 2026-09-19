<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um91gjswm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="um91gjswm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:exposure-alt" /></template>
