<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voiqsdbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="voiqsdbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:knife-thrust" /></template>
