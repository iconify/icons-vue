<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tve0zhb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="tve0zhb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-down-to-line" /></template>
