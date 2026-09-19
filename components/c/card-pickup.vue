<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcq1m_bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcq1m_bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-pickup" /></template>
