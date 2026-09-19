<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t42fs85ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="t42fs85ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:compass" /></template>
