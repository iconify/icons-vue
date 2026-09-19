<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_mq6qb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_mq6qb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:love-song" /></template>
