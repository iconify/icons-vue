<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp3xwkydj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wp3xwkydj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-063" /></template>
