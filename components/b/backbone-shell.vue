<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd6quovps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd6quovps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:backbone-shell" /></template>
