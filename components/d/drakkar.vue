<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddw7wxkey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ddw7wxkey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drakkar" /></template>
