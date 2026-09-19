<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywx0g0bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywx0g0bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barbecue" /></template>
