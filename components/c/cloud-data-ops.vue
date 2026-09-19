<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcp9bc3cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tcp9bc3cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-data-ops" /></template>
