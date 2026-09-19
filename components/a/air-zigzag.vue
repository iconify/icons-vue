<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojbe5ab3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojbe5ab3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:air-zigzag" /></template>
