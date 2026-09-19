<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxd2pgb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxd2pgb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lunar-wand" /></template>
