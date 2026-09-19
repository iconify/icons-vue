<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjwek1blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="hjwek1blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-sm-stroke-12" /></template>
