<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dta1_oyxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dta1_oyxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fromkai-dark" /></template>
