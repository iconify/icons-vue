<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3rf145jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3rf145jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:carrion" /></template>
