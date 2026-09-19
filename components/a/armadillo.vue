<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnerww72i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnerww72i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armadillo" /></template>
