<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccpn5mbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccpn5mbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:all-for-one" /></template>
