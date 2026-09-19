<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-n4dbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tr-n4dbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-093" /></template>
