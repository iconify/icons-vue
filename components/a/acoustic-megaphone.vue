<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q74a_vbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q74a_vbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:acoustic-megaphone" /></template>
