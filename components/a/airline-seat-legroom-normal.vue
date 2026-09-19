<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzo1he64y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="pzo1he64y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-legroom-normal" /></template>
