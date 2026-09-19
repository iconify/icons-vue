<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1c_jibuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1c_jibuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crane" /></template>
