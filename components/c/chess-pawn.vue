<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mik1ovm0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mik1ovm0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:chess-pawn" /></template>
