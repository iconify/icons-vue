<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cihrapily.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cihrapily"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bath" /></template>
