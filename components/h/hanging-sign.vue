<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te4ap0b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="te4ap0b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hanging-sign" /></template>
