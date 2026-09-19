<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swbr1du4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swbr1du4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hand-bandage" /></template>
