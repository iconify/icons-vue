<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_mebygut.css';
import '../../css/j/jmg8jub9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i_mebygut"/><path class="jmg8jub9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-note-music" /></template>
