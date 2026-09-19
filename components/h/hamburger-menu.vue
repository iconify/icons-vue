<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_w5io5_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_w5io5_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hamburger-menu" /></template>
