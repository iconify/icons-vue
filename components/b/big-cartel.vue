<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l73vfmbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l73vfmbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:big-cartel" /></template>
