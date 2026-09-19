<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc_sombtl.css';
import '../../css/c/cpua5hbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nc_sombtl"/><path class="cpua5hbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hourglass" /></template>
