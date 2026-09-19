<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx-u8bbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bx-u8bbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:buoy" /></template>
