<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_kkbc5mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_kkbc5mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hypersonic-melon" /></template>
