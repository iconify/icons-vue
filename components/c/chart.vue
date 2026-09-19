<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqgk037fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqgk037fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chart" /></template>
