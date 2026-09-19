<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_qo1duhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_qo1duhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-3-spades" /></template>
