<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_55sab2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_55sab2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chess-rook" /></template>
