<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esl9wpbmj.css';
import '../../css/h/haitiqbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="esl9wpbmj"/><path class="haitiqbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ice-accretion" /></template>
