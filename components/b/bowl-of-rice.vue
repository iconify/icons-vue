<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpk0dxbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpk0dxbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bowl-of-rice" /></template>
