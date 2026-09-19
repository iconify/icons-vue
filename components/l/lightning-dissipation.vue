<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjls1k5-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xjls1k5-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-dissipation" /></template>
