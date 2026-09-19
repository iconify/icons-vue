<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o70efid-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o70efid-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broken-heart-zone" /></template>
