<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cto2kz5ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cto2kz5ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dig-dug" /></template>
