<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iguhhz2_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iguhhz2_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:crop" /></template>
