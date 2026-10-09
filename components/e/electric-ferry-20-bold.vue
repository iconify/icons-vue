<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iams6mbdr.css';
import '../../css/k/khkze9bls.css';
import '../../css/t/t9laxhuoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iams6mbdr"/><path class="khkze9bls"/><path class="t9laxhuoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-ferry-20-bold" /></template>
