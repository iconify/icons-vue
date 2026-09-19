<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2x0b7bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d2x0b7bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:biohazard" /></template>
