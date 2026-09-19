<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okxe_6bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okxe_6bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:buy-card" /></template>
