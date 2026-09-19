<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3u4msgjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y3u4msgjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-joker" /></template>
