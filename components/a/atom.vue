<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh77clr3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qh77clr3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:atom" /></template>
