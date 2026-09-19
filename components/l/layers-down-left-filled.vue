<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsvcw96ah.css';
import '../../css/y/yal5mhbcs.css';
import '../../css/k/kbk3tibjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsvcw96ah"/><path class="yal5mhbcs"/><path class="kbk3tibjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-down-left-filled" /></template>
