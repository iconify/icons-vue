<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_chib4c.css';
import '../../css/j/jeuojelkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u1_chib4c"/><path class="jeuojelkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-check-20" /></template>
