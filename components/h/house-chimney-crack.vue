<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzba8cryx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="yzba8cryx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-chimney-crack" /></template>
