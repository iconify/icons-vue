<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx0171-hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="wx0171-hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:arrow-right" /></template>
