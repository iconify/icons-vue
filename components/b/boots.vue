<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouulk7_aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouulk7_aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boots" /></template>
