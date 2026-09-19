<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvlbvccgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tvlbvccgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:calendar-half-year" /></template>
