<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eid4dliao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="eid4dliao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:atom" /></template>
