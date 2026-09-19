<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_n6je90w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_n6je90w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bracers" /></template>
