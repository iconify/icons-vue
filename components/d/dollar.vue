<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su1d2xb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="su1d2xb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:dollar" /></template>
