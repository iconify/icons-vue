<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iscl_zfgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iscl_zfgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blacksmith" /></template>
