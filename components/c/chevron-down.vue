<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izq-akrqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="izq-akrqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-down" /></template>
