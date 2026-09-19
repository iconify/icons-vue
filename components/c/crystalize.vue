<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq_uh0yba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bq_uh0yba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crystalize" /></template>
