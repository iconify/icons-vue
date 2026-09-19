<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdi7so47j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdi7so47j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:all-seeing-eye" /></template>
