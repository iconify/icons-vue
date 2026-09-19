<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh0i0ccvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dh0i0ccvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:kit-medical" /></template>
