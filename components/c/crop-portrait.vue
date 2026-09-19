<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtud8ramv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="mtud8ramv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-portrait" /></template>
