<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw_x7sqyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lw_x7sqyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:horn-internal" /></template>
