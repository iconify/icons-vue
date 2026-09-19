<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2df7obqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="o2df7obqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hdr-weak" /></template>
