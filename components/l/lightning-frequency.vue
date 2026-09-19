<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3v5ssbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3v5ssbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-frequency" /></template>
