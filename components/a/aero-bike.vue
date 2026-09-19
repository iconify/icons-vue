<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdkervi1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vdkervi1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:aero-bike" /></template>
