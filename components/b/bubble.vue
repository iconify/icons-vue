<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slysjnbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="slysjnbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:bubble" /></template>
