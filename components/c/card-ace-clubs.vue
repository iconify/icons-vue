<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2tphjbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2tphjbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-ace-clubs" /></template>
