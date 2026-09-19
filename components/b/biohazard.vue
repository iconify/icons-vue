<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwjh3lyto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwjh3lyto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:biohazard" /></template>
