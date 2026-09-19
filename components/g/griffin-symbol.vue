<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyfrjcbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qyfrjcbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:griffin-symbol" /></template>
