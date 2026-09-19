<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zat54qabm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zat54qabm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lotus-flower" /></template>
