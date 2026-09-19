<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt_ut7wjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt_ut7wjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:banana" /></template>
