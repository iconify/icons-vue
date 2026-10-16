<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01dflzvf.css';
import '../../css/d/dlhh58bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="dlhh58bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bubble-20-bold" /></template>
