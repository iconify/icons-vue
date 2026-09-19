<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-3m_utop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-3m_utop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hand-grip" /></template>
