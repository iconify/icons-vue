<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5k1i-lbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5k1i-lbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:doublet" /></template>
