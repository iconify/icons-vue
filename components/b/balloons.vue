<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npiyv7b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npiyv7b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:balloons" /></template>
