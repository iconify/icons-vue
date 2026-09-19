<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxtm2khtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxtm2khtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:checkered-flag" /></template>
