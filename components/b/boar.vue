<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avia07bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avia07bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boar" /></template>
