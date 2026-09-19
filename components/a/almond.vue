<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg7r2pbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gg7r2pbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:almond" /></template>
