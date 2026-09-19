<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-sm-zscq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-sm-zscq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lighthouse" /></template>
