<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e82dw-bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e82dw-bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:interceptor-ship" /></template>
