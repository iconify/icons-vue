<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whk9toiwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="whk9toiwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chart-pie" /></template>
