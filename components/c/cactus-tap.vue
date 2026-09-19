<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s78vxsbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s78vxsbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cactus-tap" /></template>
