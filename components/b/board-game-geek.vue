<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6p7jc9_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o6p7jc9_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:board-game-geek" /></template>
