<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jza233_yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jza233_yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gotify-light" /></template>
