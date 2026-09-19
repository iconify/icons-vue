<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf6zrjvvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xf6zrjvvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lockpicks" /></template>
