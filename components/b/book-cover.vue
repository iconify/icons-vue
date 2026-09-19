<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxdxw7bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxdxw7bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:book-cover" /></template>
