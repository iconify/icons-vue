<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcaebbcnz.css';
import '../../css/n/n2luvz5yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcaebbcnz"/><path class="n2luvz5yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:board-game-dice-2-bold" /></template>
