<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v99dkbc9l.css';
import '../../css/l/ltc2--b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v99dkbc9l"/><path class="ltc2--b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-bottle-20" /></template>
