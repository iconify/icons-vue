<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdrc77bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrc77bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-caret-up-square" /></template>
