<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adwhckb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adwhckb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armadillo-tail" /></template>
