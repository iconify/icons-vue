<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n58_tkbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n58_tkbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fast-backward-button" /></template>
