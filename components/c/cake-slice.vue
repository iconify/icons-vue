<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq6t0xbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eq6t0xbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cake-slice" /></template>
