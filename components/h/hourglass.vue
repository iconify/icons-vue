<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agu2bybpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="agu2bybpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hourglass" /></template>
