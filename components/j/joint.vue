<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjyo4ebzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjyo4ebzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:joint" /></template>
