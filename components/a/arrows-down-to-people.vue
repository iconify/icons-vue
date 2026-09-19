<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxdwi4bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jxdwi4bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-down-to-people" /></template>
