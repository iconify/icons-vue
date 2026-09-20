<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpny1ho_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpny1ho_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-up" /></template>
