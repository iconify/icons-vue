<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_c-xb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vd_c-xb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bullet-bill" /></template>
