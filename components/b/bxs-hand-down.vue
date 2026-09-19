<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-r8gnast.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-r8gnast"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hand-down" /></template>
