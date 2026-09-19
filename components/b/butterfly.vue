<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciz_0dbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ciz_0dbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:butterfly" /></template>
