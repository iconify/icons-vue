<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6s0rjbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l6s0rjbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-game-remix" /></template>
