<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jin3rs3na.css';
import '../../css/p/pd26jybbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jin3rs3na"/><path class="pd26jybbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:football" /></template>
