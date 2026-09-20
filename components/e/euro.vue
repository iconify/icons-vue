<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiv-hu0xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oiv-hu0xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:euro" /></template>
