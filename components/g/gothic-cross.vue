<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6b2fs24e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6b2fs24e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gothic-cross" /></template>
