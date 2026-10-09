<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ezl7eqf.css';
import '../../css/m/mgkn3accm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i0ezl7eqf"/><path class="mgkn3accm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-20-bold" /></template>
