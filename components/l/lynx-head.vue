<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu5wnmgll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pu5wnmgll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lynx-head" /></template>
