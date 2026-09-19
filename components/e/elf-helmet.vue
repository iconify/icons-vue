<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggn1yhbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ggn1yhbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:elf-helmet" /></template>
