<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dye_bny7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dye_bny7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:earwig" /></template>
