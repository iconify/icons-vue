<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozdtx1bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozdtx1bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:archery-target" /></template>
