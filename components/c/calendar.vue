<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ot--9xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w1ot--9xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:calendar" /></template>
