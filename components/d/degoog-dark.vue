<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnm7m2cva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnm7m2cva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:degoog-dark" /></template>
