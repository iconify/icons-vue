<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqv9c1ert.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqv9c1ert"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ecology" /></template>
