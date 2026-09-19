<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikr46kbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikr46kbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drinking" /></template>
