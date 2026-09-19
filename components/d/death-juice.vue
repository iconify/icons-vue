<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db2na1wqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="db2na1wqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:death-juice" /></template>
