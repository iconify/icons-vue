<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh00p_b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hh00p_b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hockey-48-bold" /></template>
