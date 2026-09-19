<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyq595bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyq595bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flying-flag" /></template>
