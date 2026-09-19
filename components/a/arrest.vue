<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrbl_6kht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qrbl_6kht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrest" /></template>
