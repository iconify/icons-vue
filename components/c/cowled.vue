<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb8b2yvin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yb8b2yvin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cowled" /></template>
