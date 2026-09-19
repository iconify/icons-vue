<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tij_f1buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tij_f1buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:d3-js" /></template>
