<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7hd_lbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l7hd_lbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chess-pawn-solid" /></template>
