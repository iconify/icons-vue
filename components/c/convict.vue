<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrgy8szvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrgy8szvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:convict" /></template>
