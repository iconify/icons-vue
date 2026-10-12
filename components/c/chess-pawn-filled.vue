<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8eaavice.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8eaavice"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chess-pawn-filled" /></template>
