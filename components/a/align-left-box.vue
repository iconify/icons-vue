<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2wjdq7ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2wjdq7ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:align-left-box" /></template>
