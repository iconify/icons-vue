<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux8t0hbvv.css';
import '../../css/s/s9s7xp23i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ux8t0hbvv"/><path class="s9s7xp23i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calculator" /></template>
