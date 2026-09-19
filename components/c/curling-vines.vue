<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaxx29_vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aaxx29_vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:curling-vines" /></template>
