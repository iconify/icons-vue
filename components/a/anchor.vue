<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfexojt-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfexojt-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:anchor" /></template>
