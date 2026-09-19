<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2g9aacmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2g9aacmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hospital" /></template>
