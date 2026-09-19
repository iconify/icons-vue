<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq_q15z3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qq_q15z3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:guilded" /></template>
