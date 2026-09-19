<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y59k7xduf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y59k7xduf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-x-square" /></template>
