<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzy_64bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzy_64bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fallout-shelter" /></template>
