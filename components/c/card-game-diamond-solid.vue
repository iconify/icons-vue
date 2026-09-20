<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx3ex45_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx3ex45_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:card-game-diamond-solid" /></template>
