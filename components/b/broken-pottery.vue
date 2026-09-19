<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfo0o6wea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfo0o6wea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broken-pottery" /></template>
