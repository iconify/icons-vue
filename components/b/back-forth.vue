<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f81_s03iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f81_s03iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:back-forth" /></template>
