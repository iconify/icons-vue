<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oji3akbpr.css';
import '../../css/y/yvg_m-b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oji3akbpr"/><path class="yvg_m-b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:iso-filled" /></template>
