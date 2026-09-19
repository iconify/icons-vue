<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhb4ejb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhb4ejb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crow-nest" /></template>
