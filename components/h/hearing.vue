<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2b_qbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="t_2b_qbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hearing" /></template>
