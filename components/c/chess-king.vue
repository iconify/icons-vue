<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etkmd655w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="etkmd655w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:chess-king" /></template>
