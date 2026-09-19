<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2q6ibgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wb2q6ibgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:files" /></template>
