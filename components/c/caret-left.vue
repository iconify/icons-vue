<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij_t_sbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ij_t_sbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-left" /></template>
