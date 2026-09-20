<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck1sin1dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck1sin1dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:gauge" /></template>
