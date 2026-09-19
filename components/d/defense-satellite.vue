<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3su7f1mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3su7f1mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:defense-satellite" /></template>
