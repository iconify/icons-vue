<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr6fn7b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="wr6fn7b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-download" /></template>
