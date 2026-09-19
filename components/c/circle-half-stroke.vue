<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utqr_sbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="utqr_sbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-half-stroke" /></template>
