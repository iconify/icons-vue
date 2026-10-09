<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itz70zb2a.css';
import '../../css/r/ry8p8oeqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itz70zb2a"/><path class="ry8p8oeqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dining-20" /></template>
