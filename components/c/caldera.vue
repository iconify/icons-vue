<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue6tg1ivu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue6tg1ivu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:caldera" /></template>
