<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f98v0hbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f98v0hbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calculator-gloss" /></template>
