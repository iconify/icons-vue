<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9z3ehbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9z3ehbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bed" /></template>
