<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wknyjab-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wknyjab-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ages" /></template>
