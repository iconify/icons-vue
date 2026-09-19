<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyhrs9bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="qyhrs9bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alert-circle-o" /></template>
