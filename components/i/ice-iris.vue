<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxwebqvgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxwebqvgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-iris" /></template>
