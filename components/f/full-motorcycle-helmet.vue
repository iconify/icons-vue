<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r15r1itiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r15r1itiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:full-motorcycle-helmet" /></template>
