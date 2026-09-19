<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzht7_bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzht7_bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrow-cursor" /></template>
