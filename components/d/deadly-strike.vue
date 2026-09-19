<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj_2_qbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bj_2_qbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:deadly-strike" /></template>
