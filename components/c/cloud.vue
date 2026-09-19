<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyra8pbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="gyra8pbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud" /></template>
