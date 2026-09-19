<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqz63qbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqz63qbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:half-tornado" /></template>
