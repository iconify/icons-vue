<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l03wl_bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l03wl_bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jungle" /></template>
