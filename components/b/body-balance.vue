<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubw56lkls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ubw56lkls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:body-balance" /></template>
