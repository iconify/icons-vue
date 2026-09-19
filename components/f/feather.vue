<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl10adc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl10adc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:feather" /></template>
