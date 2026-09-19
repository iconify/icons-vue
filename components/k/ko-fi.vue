<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq22e_95b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fq22e_95b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ko-fi" /></template>
