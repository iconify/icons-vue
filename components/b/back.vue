<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz1y3cc3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":489,"height":628};
const content = `<path class="fz1y3cc3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:back" /></template>
