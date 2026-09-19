<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inexm0bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="inexm0bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:edge-crack" /></template>
