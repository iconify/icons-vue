<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc27174-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wc27174-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:level-crossing" /></template>
