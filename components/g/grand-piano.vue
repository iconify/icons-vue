<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5nh5bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vc5nh5bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grand-piano" /></template>
