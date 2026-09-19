<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l50k6bbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="l50k6bbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hd" /></template>
