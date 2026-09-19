<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i002w5bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i002w5bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fish-eggs" /></template>
