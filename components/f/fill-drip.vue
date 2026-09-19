<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ok3ubhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="y7ok3ubhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fill-drip" /></template>
