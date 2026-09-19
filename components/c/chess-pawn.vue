<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvww-2n-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvww-2n-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chess-pawn" /></template>
