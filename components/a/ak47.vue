<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5c1m7t2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5c1m7t2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ak47" /></template>
