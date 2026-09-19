<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hep5b_btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hep5b_btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:heart-crack" /></template>
