<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrjc3vb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrjc3vb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-arc" /></template>
