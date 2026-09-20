<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rngp1fbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rngp1fbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:horse-head-solid" /></template>
