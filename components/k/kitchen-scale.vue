<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqnfig0ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqnfig0ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kitchen-scale" /></template>
