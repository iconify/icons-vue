<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4wmv8try.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4wmv8try"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bottle-vapors" /></template>
